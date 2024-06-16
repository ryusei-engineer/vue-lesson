<script setup>
import HelloWorld from './components/HelloWorld.vue'
import TheWelcome from './components/TheWelcome.vue'
import { ref, watchEffect } from 'vue'
const count = ref(0);
watchEffect(()=>{
  console.log(count.value);
})
</script>

<template>
<p>{{ count }}</p>
<button @click="count++">add</button>
</template>

