<template>
  <nav class="flex justify-content-between align-items-center w-full text-white p-4 fixed top-0 left-0 shadow-md">
    <div class="flex flex-row align-items-center">
      <img src="" class="w-10rem" alt="Logo">
    </div>

    <div class="flex gap-4">
      <RouterLink to="/" class="nav-link">Home</RouterLink>
      <RouterLink to="/about" class="nav-link">About</RouterLink>
      <RouterLink to="/products" class="nav-link">Products</RouterLink>
      <RouterLink to="/contact" class="nav-link">Contact</RouterLink>
    </div>
  </nav>
</template>

<script setup lang="ts">
</script>

<style scoped>
nav{
  background: #2c8f96;
}
/* Styling for navigation links */
.nav-link {
  text-decoration: none;
  color: white;
  font-weight: bold;
  transition: color 0.3s ease;
}

.nav-link:hover {
  color: #dbeafe; /* Lighter blue */
}
</style>
