<script setup>
import Footer from './components/Footer.vue';
import Header from './components/Header.vue';
import { RouterLink, RouterView } from 'vue-router'
</script>

<template>


  <Header />
  <RouterView />
  <Footer />
</template>

<style>
body {
  font-family: Arial, sans-serif;
  line-height: 1.6;
  color: #333;
  padding: 20px;
}
</style>