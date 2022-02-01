<script lang="ts" setup>
import { useFetch } from "#app";

await new Promise(resolve => setTimeout(() => resolve(true), 1000))
const { data } = await useFetch("https://jsonplaceholder.typicode.com/users");
</script>
<template>
  <div>
    <strong>async component</strong>
    {{ data }}
  </div>
</template>
