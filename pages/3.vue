<script  lang="ts" setup>
import useComponentLoader from "~/composables/useComponentLoader";
</script>

<template>
  <div>
    <h1>async</h1>
    <hr>
    <component
        :is="useComponentLoader({ component: 'async-component' })"
    ></component>
  </div>
</template>