<script setup>
import NavBar from './components/NavBar.vue';
import FooterComp from './components/FooterComp.vue';
import Banner from './components/Banner.vue';

import { ref } from 'vue';

const userFirstName = ref('John Doe')
</script>

<template>
  <NavBar />
  <Banner>
    <span>{{userFirstName}}</span>
  </Banner>
  <div class="p-6 bg-amber-300 flex flex-col gap-10 text-3xl" id="main-page-results">
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