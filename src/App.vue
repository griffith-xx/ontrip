<script setup>
import Navbar from "./sections/Navbar.vue";
import Hero from "./sections/Hero.vue";
import Categories from "./sections/Categories.vue";
import Video from "./sections/Video.vue";
import Popular from "./sections/Popular.vue";
import Trip from "./sections/Trip.vue";
import FeedBack from "./sections/FeedBack.vue";
import Subscribe from "./sections/Subscribe.vue";
import Footer from "./sections/Footer.vue";
</script>

<template>
  <div class="font-prompt antialiased max-w-[1440px] mx-auto bg-[#E2EBF0]">
    <Navbar />
    <Hero />
    <div class="max-w-[1200px] w-full mx-auto">
      <Categories />
      <Video />
      <Popular />
      <Trip />
      <FeedBack />
      <Subscribe />
    </div>
    <Footer />
  </div>
</template>
