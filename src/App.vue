<template>
  <div id="app">
    <Header/>
    <Main/>
    
  </div>
</template>

<script>
import Header from './components/Header.vue'
import Main from './components/Main.vue'

export default {
  name: 'App',
  components: {
    Header,
    Main
  }
}
</script>

<style lang="scss">
#app {
  display: flex;
  flex-direction: column;
  flex-wrap: wrap;
  width: 100vh;
}
</style>
