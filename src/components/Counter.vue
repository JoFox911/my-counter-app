<script setup>
import { useCounterStore } from '@/stores/counter'

const counter = useCounterStore()
</script>

<template>
  <h1>Count: {{ counter.count }}</h1>
  <button @click="counter.increment">Increment</button>
  <button @click="counter.decrement">Decrement</button>
</template>

