<!-- src/components/Header.vue -->
<template>
  <header class="header">
    <nav>
      <ul>
        <li><router-link to="/">Home</router-link></li>
        <li><router-link to="/resume">Resume</router-link></li>
      </ul>
    </nav>
  </header>
</template>

<script setup>
</script>

<style scoped>
.header {
  background-color: #f8f9fa;
  padding: 1rem;
}
nav ul {
  list-style: none;
  display: flex;
  gap: 1rem;
}
</style>
