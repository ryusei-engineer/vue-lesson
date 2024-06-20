<script setup>
import HelloWorld from './components/HelloWorld.vue'
import TheWelcome from './components/TheWelcome.vue'
import { ref } from 'vue'
const ok = ref(true)
</script>

<template>
<button @click="ok = !ok">反転</button>
<template v-if="ok">
  <p>true1</p>
  <p>true2</p>
</template>

<p v-else="ok">false</p>
</template>
<style>
</style>

