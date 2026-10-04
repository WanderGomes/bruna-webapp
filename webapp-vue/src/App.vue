<script setup lang="ts">
import { RouterLink, RouterView } from 'vue-router'
import Header from "@/components/Header.vue";
import Menu from "@/components/Menu.vue";
import Footer from "@/components/Footer.vue";
import HomeView from "@/views/HomeView.vue";
import AboutView from "@/views/partials/About.vue";
</script>

<template>
  <Header/>

  <Menu />

  <main>
    <RouterView />
  </main>

  <Footer/>
</template>

<style lang="scss" scoped>
  @import "assets/styles/styles";
</style>
