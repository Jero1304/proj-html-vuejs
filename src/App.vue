<script setup>
import Navbar from './components/Navbar.vue';
import Hero from './components/Hero.vue';
import Service from './components/Service.vue';
import ChannelYT from './components/ChannelYT.vue';
import Playlist from './components/Playlist.vue';
</script>

<template>
  <header>
    <Navbar/>
    <Hero/>
  </header>

  <main>
    <Service/>
    <ChannelYT/>
    <Playlist/>
  </main>
</template>

<style lang="scss">
      body{
        height: 100vh;
        overflow-x: auto;
      }
</style>
