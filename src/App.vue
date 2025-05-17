<script setup>

import Navbar from "./components/NavbarComponent.vue";
import Footer from "./components/FooterComponent.vue";

</script>

<template>
  <Navbar />
  <router-view> </router-view>
  <div class="mflex flex-col min-h-screen px-4 py-6">
    </div>
    <Footer />
</template>
