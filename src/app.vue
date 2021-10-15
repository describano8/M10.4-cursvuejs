<template>
  <div id="app">
    <img alt="logo del proyecto" src="./images/LOGO.JPG">
    <HolaMundo msg="¡Hola Mundo!"/>
  </div>
</template>

<script>
import HolaMundo from './components/Test.vue'
export default {
  name: 'App',
  components: {
    HolaMundo
  }
}
</script>

<style>
#app {
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
}
</style>