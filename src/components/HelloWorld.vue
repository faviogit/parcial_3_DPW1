<script setup>
import { ref } from 'vue'

const count = ref(0)

const increment = () => {
  count.value += 2
}

const decrement = () => {
  count.value -= 2
}
</script>

<template>
  <div>
    <p>Contador: {{ count }}</p>
    <button @click="increment">Incrementar (+2)</button>
    <button @click="decrement">Reducir (-2)</button>
  </div>
</template>

<style scoped>
button {
  margin: 0.5rem;
}
</style>
