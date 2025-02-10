<script setup lang="ts">
import { ref } from 'vue';

const x = ref(0);
</script>

<template>
  <main>
    Hello World {{ x * 2 }}
    <br />
    <button @click="x += 1">Increase</button>
  </main>
</template>
