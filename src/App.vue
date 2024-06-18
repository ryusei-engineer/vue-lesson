<script setup>
import HelloWorld from './components/HelloWorld.vue'
import TheWelcome from './components/TheWelcome.vue'
</script>

<template>
<p :class="{red: true, border: false}">test</p>
</template>
<style>
.red{
  color: red;
}

.border{
  border: 1px solid black;
}
</style>

