<script setup lang="ts">
import { RouterView } from 'vue-router'
import NavBar from "./components/NavBar.vue"
import Footer from "./components/Footer.vue"
</script>

<template>
  <NavBar />
  <main>
    <RouterView />
  </main>
  <Footer />
</template>

<style scoped lang="scss">
@import "./assets/main.css";
</style>
