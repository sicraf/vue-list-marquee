<template>
  <div id="app">
    <Demo/>
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
  font-family: 'Avenir', Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  /* text-align: center; */
  color: #2c3e50;
  /* margin-top: 60px; */
}

body {
  margin: 0;
  padding: 0;
}
</style>
