<script setup lang="ts">
import { ref } from 'vue'

const counter = ref(19)
</script>

<template>
  <main>
    Home View
    {{ counter }}

    <button @click="counter++">Increment</button>
    <button @click="counter--">Decrement</button>
  </main>
</template>
