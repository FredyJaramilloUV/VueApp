<template>
  <h1 v-show="age < 18">Eres menor de edad</h1>
  <h1 v-show="age > 18">Eres mayor de edad</h1>
</template>

<script setup>
const age = 3
</script>

<style>
</style>
