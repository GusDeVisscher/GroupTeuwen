<script setup lang="ts">
import { RouterLink, RouterView } from 'vue-router'
import NavBar from './components/NavBar.vue';
import FooterInfo from './components/FooterInfo.vue';
</script>

<template>
  <div class="flex flex-column justify-content-between">
    <NavBar />
    <RouterView />
    <FooterInfo/>
  </div>
</template>

<style scoped>
/* Ensures the layout stretches to full height */

</style>

