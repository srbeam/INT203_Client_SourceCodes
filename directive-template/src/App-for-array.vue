<script setup>
const foods = ['steak', 'salad', 'tomyum', 'fried rice']
</script>

<template>
  <h1>Food List</h1>
  <ul>
    <li v-for="(food, index) in foods" :key="index">#{{index}}{{ food }}</li>
  </ul>
</template>

<style></style>