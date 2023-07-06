<script setup>
const data = ref('layout data');
</script>

<template>
  <div>
    layout: {{ data }}
    <slot />
  </div>
</template>
