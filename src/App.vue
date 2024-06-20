<script setup>
import HelloWorld from './components/HelloWorld.vue'
import TheWelcome from './components/TheWelcome.vue'
import { ref } from 'vue'
const ok = ref(true)
</script>

<template>
<p v-if="ok">test</p>
</template>
<style>
</style>

