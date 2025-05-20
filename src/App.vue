<script setup>
import Navbar from "./components/NavbarComponent.vue";
import Footer from "./components/FooterComponent.vue";
</script>

<template>
  <Navbar />
  <router-view> </router-view>
  <div class="flex flex-col min-h-screen px-4 py-6"></div>
  <Footer />
</template>
