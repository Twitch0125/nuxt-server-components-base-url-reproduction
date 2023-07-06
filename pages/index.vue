<script setup>
const showComponent = ref(true);
</script>
<template>
  <div>
    <button @click="showComponent = !showComponent">toggle</button>
    <ServerComponent v-if="showComponent" />
  </div>
</template>
