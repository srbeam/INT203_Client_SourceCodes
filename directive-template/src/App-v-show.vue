<script setup>
const count = 1
</script>

<template>
  <p v-show="count">Counter: {{ count }}</p>
  <p> UserName: {{username }}</p>
  <p v-show="!username" style="color: red" > Please enter your name!</p> 

<!-- ไม่ใส่ username จะเเสดง true -->
<!-- ใส่ username จะไม่เเสดง flase -->
</template>

<style></style>