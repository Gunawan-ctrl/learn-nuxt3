<script setup>
useHead({
  title: "Home Page",
});

const { data } = await useFetch("/api/userdetails");
</script>

<template>
  <h1>Home Page</h1>
  <p>
    {{ data.msg }}
  </p>
</template>
