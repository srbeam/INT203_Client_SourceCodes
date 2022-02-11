<script setup>
const headingStyle = "color: red"
const paraStyle = "text-decoration: underline" 
const imagePath = "../public/images/mypic..jpg"
</script>
 
<template>
<h1 :style ="headingStyle"> INT203 Client side </h1>
<p :style ="paraStyle"> Umaporn </p>
<img src = "./assets/logo.png">
<img :src="imagePath " alt="pic" srcset="">

</template>
 
<style>

</style>