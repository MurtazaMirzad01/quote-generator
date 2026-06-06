<script setup>
  import {ref} from 'vue'
  const name = ref('Rachel')

</script>

<template>
  <main>
    <h1>{{ name }}</h1>
  </main>
</template>

<style scoped>
  main {
    background-color: #42b983;
    color: white;
    padding: 20px;  }
</style>