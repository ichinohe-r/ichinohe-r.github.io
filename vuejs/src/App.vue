<template>
  <div id="app">
    <TopPage msg="Vue.js App"/>
  </div>
</template>

<script>
import TopPage from './components/TopPage.vue'

export default {
  name: 'app',
  components: {
    TopPage
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
