<script setup>
import HelloWorld from './components/HelloWorld.vue'
import TheWelcome from './components/TheWelcome.vue'
import { ref } from 'vue'
let count = ref(0);
function increment(){
  count.value++;
}
</script>

<template>
{{ count }} 
<button @click="increment"></button>
</template>

