<script lang="ts" setup>
import { useFetch } from "#app";

const { data } = await useFetch("https://jsonplaceholder.typicode.com/users");
</script>
<template>
  <div>
    <strong>async component</strong>
    {{ data }}
  </div>
</template>
