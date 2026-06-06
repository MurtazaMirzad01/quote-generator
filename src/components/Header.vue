<script setup>
    import {ref} from 'vue'
    const framework =  ref('Vue.js')

</script>

<template>
  <header>
    <h1>Welcome to {{ framework }}</h1>
  </header>
</template>

<style scoped>
  header {
    background-color: #42b983;
    color: white;
    padding: 20px;
  }
</style>