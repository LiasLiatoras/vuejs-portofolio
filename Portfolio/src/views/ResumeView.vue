<script setup>
import Navbar from "./../components/Navbar.vue";
</script>

<template>
  <Navbar />
  <div class="about">
    <h1>This is an resume page</h1>
  </div>
</template>

<style>
@media (min-width: 1250px) {
  .about {
    min-height: 100vh;
    display: flex;
    align-items: center;
  }
}
</style>
