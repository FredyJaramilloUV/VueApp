<template>
  <p v-bind:class = "{'danger': hasError }"> El mensaje tiene un error si esta rojo </p>
</template>

<script setup>
const hasError = true
</script>

<style>
.danger{
  color: red;
}
</style>
