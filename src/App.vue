<script setup>
import HelloWorld from './components/HelloWorld.vue'
import TheWelcome from './components/TheWelcome.vue'
import { ref } from 'vue'
const array = ref([
  { id: 1, value: "A"},
  { id: 2, value: "B"},
  { id: 3, value: "C"}
])
</script>

<template>
<button @click="array.shift()"></button>
<p v-for="char in array" :key="char.id"><input type="text">{{ char.value }}</p>
</template>
<style>
</style>

