<script setup lang="ts">
await new Promise(resolve => setTimeout(() => resolve(true), 1000))
</script>
<template>
  <div>
    <h1>index</h1>
    <hr>
    <normal-component />
  </div>
</template>