<template>
  <div id="app">
    <Demo />
  </div>
</template>

<script>
import Demo from './components/Demo.vue'

export default {
  name: 'App',
  components: {
    Demo
  }
}
</script>

<style>
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  font-size: 18px;
  color: #2c3e50;
  margin: 60px auto;
  width: 40%;
}
</style>
