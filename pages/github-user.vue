<script setup>
const { data: user } = useFetch("https://api.github.com/users/gunawan-ctrl");
</script>

<template>
  <h1>{{ user?.name }}</h1>
  <h1>{{ user?.location }}</h1>
  <p>{{ user?.following }}</p>
</template>
