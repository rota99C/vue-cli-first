<template>
  <div id="app">
    <img alt="Vue logo" src="./assets/logo.png">
    <TitleVue/>
    <Hero/>


  </div>
</template>

<script>
import TitleVue from './components/TitleVue.vue'
import Hero from './components/Hero.vue'


export default {
  name: 'App',
  components: {
    TitleVue,
    Hero
  }
}
</script>

<style lang="scss">
*{
  padding: 0;
  margin: 0;
  box-sizing: 0;
  }
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
}
</style>
