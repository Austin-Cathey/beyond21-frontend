<script setup>
import { ref } from "vue";
</script>

<template>
  <div id="nav">
    <router-link to="/">Home</router-link>
    <router-link to="/login">Login</router-link>
    <router-link to="/signup">Signup</router-link>
  </div>
  <router-view />
  <div id="app"></div>
</template>
<style scoped></style>
