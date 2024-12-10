<script setup>
import SojMenu from "./components/soj-menu.vue";
import SojCarousel from "./components/soj-carousel.vue";
import SojUserSelf from "./components/soj-user-self.vue";
</script>

<template>
  <d-layout>
    <d-header>
      <soj-menu></soj-menu></d-header>
    <d-content>
      <d-row>
        <d-col span="20" class="dcol">
          <soj-carousel></soj-carousel></d-col>
        <d-col span="4" class="dcol">
          <soj-user-self></soj-user-self></d-col>
      </d-row>
    </d-content>
  </d-layout>
</template>

<style scoped>
#app{
width: 100%;
}
.dcol{
  margin: 5px;
}
</style>
