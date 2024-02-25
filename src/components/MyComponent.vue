<script setup>
import {reactive, ref} from "vue";
const count = ref(0)

const inc = () => {
  count.value ++;
}
</script>

<template>
  <button @click="inc">+</button>
  <p v-text="count"></p>
</template>

<style scoped>
.red{
  color:red;
}
</style>