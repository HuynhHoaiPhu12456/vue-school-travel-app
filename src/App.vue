<script setup>
import { RouterLink, RouterView } from 'vue-router'
import TheNavigation from './components/TheNavigation.vue';
</script>

<template>
  <TheNavigation />
  <div class="container">
    <RouterView />
  </div>
</template>

<style scoped></style>
