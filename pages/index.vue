<template>
  <div>this is the home page</div>
</template>

<script setup>
useSeoMeta({
  title: "Main Page",
  description: "This is the main page",
  ogTitle: "Main Page",
  ogDescription: "This is the main page",
  ogImage: "[og:image]",
  ogUrl: "[og:url]",
  twitterTitle: "Main Page",
  twitterDescription: "This is the main page",
  twitterImage: "[twitter:image]",
  twitterCard: "summary",
});

useHead({
  htmlAttrs: {
    lang: "en",
  },
});
</script>
