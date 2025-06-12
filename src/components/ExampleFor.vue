<template>
    <li v-for="country in countries" v-bind:key="country">{{country}} </li>
</template>

<script setup>
import { ref } from 'vue'
const countries = ref([
  'spain', 'France', 'UK', 'Italy', 'portugal'
])
</script>

<style scoped>
</style>
