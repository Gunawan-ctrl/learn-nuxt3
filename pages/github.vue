<script setup>
const { data: users } = useFetch("https://api.github.com/users");
</script>

<template>
  <h1>Github users</h1>
  <div v-for="user in users" :key="user.id">
    <h2>{{ user.login }}</h2>
    <p>name: {{ user?.name }}</p>
    <p>id is: {{ user.id }}</p>
  </div>
</template>
