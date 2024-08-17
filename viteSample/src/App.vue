<script setup>
import { ref } from 'vue';

const num = ref(2)

const add = () => {
  num.value++
}

</script>

<template>
  {{ num }}
  <button type="button" @click="add">點我</button>
</template>

<style></style>