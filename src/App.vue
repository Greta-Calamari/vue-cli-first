<template>
  <div id="app">
    <img alt="Vue logo" src="./assets/logo.png">
    
    <TitleTitle/>
    <HeroHero/>

  </div>
</template>

<script>

import HeroHero from './components/HeroHero.vue'
import TitleTitle from './components/TitleTitle.vue'


export default {
  name: 'App',
  components: {
    
    TitleTitle,
    HeroHero,
    
    
  }
}
</script>

<style lang="scss">
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
}
</style>
