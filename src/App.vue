<script setup>
import Navbar from './components/Navbar.vue';
import Carousel from './components/Carousel.vue';
import Footer from './components/Footer.vue'

</script>

<template>
 <div id="app">
    <q-layout view="hHh lpR fFf">
      <Navbar />
      <Carousel/>
      <Footer/>
    </q-layout>
  </div>
</template>

<style scoped>

</style>
