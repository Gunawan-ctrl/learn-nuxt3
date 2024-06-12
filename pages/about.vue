<script setup>
definePageMeta({
  layout: "admin",
});

useHead({
  title: "About Page",
  script: ["main.js"],
  meta: [{ name: "description", content: "This website is about nuxt.js" }],
});
</script>

<template>
  <h1>About Page</h1>
</template>
