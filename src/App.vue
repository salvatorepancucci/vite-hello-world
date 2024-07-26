<template>
  <div id="app">
    <AppTitle />
    <AppHero />
  </div>
</template>

<script>
import AppTitle from './components/AppTitle.vue'
import AppHero from './components/AppHero.vue'

export default {
  name: 'App',
  components: {
    AppTitle,
    AppHero
  }
}
</script>

<style>
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
}
</style>
