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
    <button @click="increment">Incrementar</button>
    <button @click="decrement">Decrementar</button>
  </div>
</template>

<style scoped>
button {
  margin: 1.5rem;
  padding: 0.5rem 1rem;
  background-color: #4caf50;
  color: white;
  border: none;
  border-radius: 8px;
  cursor: pointer;
}
</style>
