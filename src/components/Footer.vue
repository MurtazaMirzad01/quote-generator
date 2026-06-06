<script setup>
  import {ref} from 'vue'
  const year = ref(2024)

</script>

<template>
  <footer>
    <p>Copyright {{year}}</p>
  </footer>
</template>

<style scoped>
  footer {
    background-color: #35495e;
    color: white;
    padding: 10px;
  }
  footer p {
    color: #42b983;
  }
</style>
