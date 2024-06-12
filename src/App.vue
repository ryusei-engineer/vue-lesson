<script setup>
import HelloWorld from './components/HelloWorld.vue'
import TheWelcome from './components/TheWelcome.vue'
import { ref } from 'vue'
let count = ref(0);
function increment(num){
  count.value = num;
}
</script>

<template>
{{ count }} 
<button @click="increment(1)">1</button>
<button @click="increment(2)">2</button>
<button @click="increment(3)">3</button>
<button @click="increment(4)">4</button>
<button @click="increment(5)">5</button>
</template>

