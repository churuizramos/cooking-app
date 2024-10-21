<script setup>
import NavBar from './components/NavBar.vue';
import FooterComp from './components/FooterComp.vue';
</script>

<template>
    <NavBar />
    <div class="p-6 bg-amber-300 flex flex-col gap-6" id="main-page-results">
      <div id="carousel-1">
        <p>Carousel 1</p>
      </div>
      <div id="carousel-1">
        <p>Carousel 2</p>
      </div>
      <div id="carousel-1">
        <p>Carousel 3</p>
      </div>
    </div>
    <FooterComp />
</template>

<style scoped>

</style>
