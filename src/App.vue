<template>
  <div id="app">
    <ComingSoon/>
  </div>
</template>

<script>
import ComingSoon from './components/ComingSoon.vue'

export default {
  name: 'app',
  components: {
    ComingSoon
  }
}
</script>

<style>
body {
  font-family: 'Avenir', Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  background-color: #2c3e50;
  color: white;
  max-width: 1000px;
  margin: 60px auto;
}
#app {

}
</style>
