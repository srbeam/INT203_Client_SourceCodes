<script setup>
const warningColor = "red";
const warningStyle = "italic";
const successText = "text-decoration:underline";
const isEmpty = false;
const hasDecor = true;
</script>

<template>
  <div>
    <p :style="{ color: warningColor, 'font-style': warningStyle }">
      This is warning text.
    </p>

    <p :style="isEmpty ? { color: 'red' } : { color: 'green' }">
      This is a style under condition
    </p>
    <p :style="[successText]">This is a success text</p>
    <p :style="[successText, decorText]">This is a success text</p>
    <p :style="[successText, hasDecor ? decorText : '']">
      This is styles under condition
    </p>
  </div>
</template>

<style>
</style>
