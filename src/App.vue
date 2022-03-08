<template>
  <div id="app">
    <!-- <img alt="Vue logo" src="./assets/logo.png"> -->
    <!-- <HelloWorld msg="Welcome to Your Vue.js App"/> -->
    <TitleItem />
    <HeroItem />
  </div>
</template>

<script>
// import HelloWorld from './components/HelloWorld.vue'
import TitleItem from './components/TitleItem.vue'
import HeroItem from './components/HeroItem.vue'

export default {
  name: 'App',
  components: {
    // HelloWorld
    TitleItem,
    HeroItem
  }
}

</script>

<style lang="scss">
@import url('https://fonts.googleapis.com/css2?family=Montserrat:wght@400;600&display=swap');

#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
}
</style>
