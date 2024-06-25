<!-- src/App.vue -->
<script setup>
import { RouterView } from 'vue-router';
import Header from './components/Header.vue';  // Adjusted import path
</script>

<template>
  <Header />
  <RouterView />
</template>

<style scoped>
/* Add any global styles here */
</style>
