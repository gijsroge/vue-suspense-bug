<script setup lang="ts">
// fake async data
await new Promise(resolve => setTimeout(() => resolve(true), 500))
</script>
<template>
  <div>
    <h1>4 route with async data</h1>
    <normal-component />
  </div>
</template>