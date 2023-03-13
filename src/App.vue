<script setup>
import Navbar from './components/Navbar.vue';
import Hero from './components/Hero.vue';
import Service from './components/Service.vue';
</script>

<template>
  <header>
    <Navbar/>
    <Hero/>
  </header>

  <main>
    <Service/>
  </main>
</template>

<style lang="scss">
      body{
        height: 100vh;
        overflow-x: auto;
      }
</style>
