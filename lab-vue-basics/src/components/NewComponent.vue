<template>
  <div>
    <h1>{{numero}}</h1>
    <button @click="sum">sumar</button>
  </div>
</template>

<script>
export default {
  name: "NewComponent",
  data() {
    return {
        numero:0,
    }
  },
  methods:{
    sum() {
        this.numero++;
    }
  }
};
</script>

<style></style>
