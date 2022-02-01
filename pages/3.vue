<script  lang="ts" setup>
import useComponentLoader from "~/composables/useComponentLoader";
</script>

<template>
  <div>
    <h1>3 route with async component that has async data</h1>
    <component
        :is="useComponentLoader({ component: 'async-component' })"
    ></component>
  </div>
</template>