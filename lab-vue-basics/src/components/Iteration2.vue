<template>
  <div>
    <h1>direct sum :</h1>
    <h1>{{ 2+2 }}</h1>
    <h1>String printed:</h1>
    <h1 @click="print">{{string}}</h1>
  </div>
</template>

<script setup>
import { ref } from "vue";
const string = ref('click me');

function print() {
  string.value = 'new string';
}
</script>

<style></style>
