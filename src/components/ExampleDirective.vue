<template>
  <h1 v-if="age < 18">Eres menor de edad</h1>
  <h1 v-else>Eres mayor de edad</h1>
</template>

<script setup>
const age = 30
</script>

<style>
</style>
