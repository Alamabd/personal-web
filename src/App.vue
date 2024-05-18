<script setup lang="ts">
import HeroSection from './components/HeroSection.vue';
import Nav from './components/Nav.vue';
</script>

<template>
  <div class="mx-12 mt-4 max-sm:mx-4">
    <Header>
      <Nav />
    </Header>
    <main>
      <HeroSection />
    </main>
  </div>
</template>

<style scoped>
</style>