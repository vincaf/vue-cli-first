<template>
  <div id="app">
    <JumboTron />
  </div>
</template>

<script>
import JumboTron from './components/JumboTron.vue'

export default {
  name: 'App',
  components: {
    JumboTron
  }
}
</script>

<style>
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #fff;
  margin: 0;
  padding: 0;
  box-sizing: border-box;
}
</style>
