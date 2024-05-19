<script setup lang="ts">
import HeroSection from './components/HeroSection.vue';
import Nav from './components/Nav.vue';
import Techstack from './components/Techstack.vue';
import Projects from './components/Projects.vue';
</script>

<template>
  <div class="mx-12 mt-4 max-sm:mx-4">
    <Header>
      <Nav />
    </Header>
    <main>
      <HeroSection />
      <Techstack />
      <Projects />
    </main>
  </div>
</template>

<style scoped>
</style>