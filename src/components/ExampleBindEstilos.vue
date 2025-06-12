<template>
  <p v-bind:style = "{'background-color' : '#ccc', color: modoOscuro}">  el mensaje con estilo y uso de v-on @</p>
    <button v-on:click="handleClick()">Cambiar color</button>
    <button @click="handleClick()">Cambiar color</button>
</template>

<script setup>
import { ref } from 'vue'
const modoOscuro = ref('#fff')
const handleClick = () => { modoOscuro.value = '#ff0000' }
</script>

<style scoped>

</style>
