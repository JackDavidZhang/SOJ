<script setup>
import SojMenu from "./components/soj-menu.vue";
import SojCarousel from "./components/soj-carousel.vue";
</script>

<template>
  <d-layout>
    <d-header>
      <soj-menu></soj-menu></d-header>
    <d-content>
      <soj-carousel></soj-carousel>
    </d-content>
  </d-layout>
</template>

<style scoped>
#app{
width: 100%;
}
</style>
