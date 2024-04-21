<script setup>
import { RouterLink, RouterView } from "vue-router";
import Header from "./components/Header.vue";
import PokemonList from "./components/PokemonList.vue";
import HomeView from "./views/HomeView.vue";
</script>

<template>
  <Header />
 <HomeView />
</template>

<style scoped></style>
