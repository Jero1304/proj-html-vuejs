<script setup>
import Navbar from './components/Navbar.vue';
import Hero from './components/Hero.vue';
import Service from './components/Service.vue';
import ChannelYT from './components/ChannelYT.vue';
import Playlist from './components/Playlist.vue';
import HeroSubscribe from './components/HeroSubscribe.vue';
import CardService from './components/CardService.vue';
import OtherArticles from './components/OtherArticles.vue';
import HeroCitation from './components/HeroCitation.vue';
import Parteners from './components/Partners.vue'
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
    <HeroSubscribe/>
    <CardService/>
  </main>
  
  <footer>
    <OtherArticles/>
    <HeroCitation/>
    // <Parteners/>
  </footer>
</template>

<style lang="scss">
      body{
        height: 100vh;
        overflow-x: auto;
      }
</style>
