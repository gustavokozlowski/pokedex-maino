<script setup>
let names = ["A", "julio", "Coco", "Remi"];
</script>

<template>
  <ul>
    <li v-for="name in names">{{ name }} </li>
  </ul>
</template>

<style scoped>
li {
  color: black;
}
</style>
