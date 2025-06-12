<template>
  <form>
    <input type="text" v-model="inputText">
    <input type="checkbox" v-model="agree"> Acepto los terminos y condiciones
    <select v-model="country">
      <option value="Spain">Spain</option>
      <option value="UK">UK</option>
      <option value="France">France</option>
    </select>
  </form>
  <h3>{{ inputText }}</h3>
</template>

<script setup>
import { ref } from 'vue'
const country = ref('UK')
const inputText = ref('')
const agree = ref(true)
</script>

<style>
</style>
