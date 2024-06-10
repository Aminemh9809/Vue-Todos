<script setup>
import { RouterLink } from 'vue-router';
</script>

<template>
  <header class="bg-light">
    <nav class="container py-3">
      <div class="row align-items-center">
        <div class="col-auto">
          <div class="d-flex align-items-center">
            <img src="../assets/Vue_Logo_Black.png" alt="Vue Logo" class="img-fluid me-2" style="max-width: 50px;">
            <h1 class="h4 mb-0">Vue Todos</h1>
          </div>
        </div>
        <div class="col text-end">
          <ul class="list-inline mb-0">
            <li class="list-inline-item me-3">
              <router-link to="/" class="text-dark text-decoration-none">Home</router-link>
            </li>
            <li class="list-inline-item">
              <router-link to="/about" class="text-dark text-decoration-none">About</router-link>
            </li>
          </ul>
        </div>
      </div>
    </nav>
  </header>
</template>

<style scoped>
/* No custom styles needed, using Bootstrap classes */
</style>