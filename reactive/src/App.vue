<script setup>
import { ref } from 'vue'
console.clear()
const counter = ref(1)
const isEmpty = ref(false)
const item = 
// setTimeout(() => console.log(++counter), 3000)
// setInterval(() => console.log(++counter.value), 1000)
</script>

<template>
  <p>Counter: {{ counter }}</p>
  <p>Empty: {{ isEmpty }}</p>

</template>

<style></style>