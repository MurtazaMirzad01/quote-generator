<script setup>
  import {ref} from 'vue'
  const name = ref('Rachel')

  import Header from './components/Header.vue'
  import Main from './components/Main.vue'
  import Footer from './components/Footer.vue'
</script>

<template>
  <Header />
  <Main />
  <Footer />
</template>

<style scoped>
  footer {    background-color: #35495e;
    color: white;
    padding: 10px;
  }
  footer p {
    color: #42b983;
  }
</style>
