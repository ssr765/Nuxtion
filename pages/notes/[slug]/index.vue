<script setup lang="ts">
definePageMeta({
  layout: "alternative",
});

const route = useRoute();
console.log(`The slug is: ${route.params.slug}`);
</script>

<template>
  <div>note detail: {{ $route.params.slug }}</div>
</template>
