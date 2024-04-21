<script setup>
import PokemonCard from "../components/PokemonCard.vue";
</script>

<template>
  <div class="container-home">
    <PokemonCard />
  </div>
</template>

<style>

.container-home {
  display: flex;
  justify-content: center;
  align-items: center;
  background-color: coral;
  height: 100vh;
  overflow-x: hidden;
}
</style>