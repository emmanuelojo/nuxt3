<template>
  <div>
    <p>product detail for {{ id }} comes here</p>
  </div>
</template>

<script setup lang="ts">
definePageMeta({
  layout: "products",
});

const { id } = useRoute().params;
</script>

<style scoped></style>
