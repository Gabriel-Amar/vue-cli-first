<template>
  <div id="app">
    <HelloWorld />
    <TitleWord />
  </div>
</template>

<script>
import HelloWorld from './components/HelloWorld.vue'
import TitleWord from "./components/TitleWord.vue"

export default {
  name: 'App',
  components: {
    HelloWorld,
    TitleWord
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
