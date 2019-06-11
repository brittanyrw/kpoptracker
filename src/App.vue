<template>
  <div id="app">
    <Header/>
    <Groups/>
  </div>
</template>

<script>
import Header from './components/Header.vue'
import Groups from './components/Groups.vue'

export default {
  name: 'app',
  components: {
    Header,
    Groups
  }
}
</script>

<style>
#app {
  font-family: 'Avenir', Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
}
</style>
