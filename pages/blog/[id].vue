<template>
  <div>we are inside the blog</div>
  <div>Post id is {{ $route.params.id }}</div>
</template>

<script setup>
const route = useRoute();
</script>
