<script setup>
import {ref} from 'vue'
  const year = ref("2025")
  const hreeef = ref("https://www.professorpickle.com")
</script>

<template>
  <footer>
    Created by <a :href="hreeef" target="_blank">Professor Pickle</a> &copy; {{ year }}
  </footer>
</template>

<style scoped>
footer {
    position: fixed;
    margin: 0 auto;
    bottom: 0;
    text-align: center;
    color: #CCD6D9;
    padding-bottom: 20px;
}

span {
    font-family: cursive;
}
a {
    color: #CCD6D9;
}
</style>