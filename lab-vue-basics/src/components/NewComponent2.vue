<template>
  <div>
    <h1>{{ num }}</h1>
    <button @click="add">sumar</button>
  </div>
</template>

<script setup>
import { ref } from "vue";
const num = ref(3);

function add() {
  num.value++;
}
</script>

<style></style>
