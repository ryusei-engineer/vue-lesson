<script setup>
import HelloWorld from './components/HelloWorld.vue'
import TheWelcome from './components/TheWelcome.vue'
import { ref, computed } from 'vue'
const score = ref(0)
const ev = computed(()=>{
  return score.value > 3 ? 'ok' : 'no'
})
</script>

<template>
<p>{{ ev }}</p>
<button @click="score++">add</button>
</template>

