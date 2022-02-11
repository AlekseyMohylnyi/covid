<template>
  <div id="app">    
    <Header />
    <What />
    <Contagion />
  </div>
</template>

<script>
import Header from './components/Header.vue'
import What from './components/What.vue'
import Contagion from './components/Contagion.vue'

export default {
  name: 'App',
  components: {
    Header,
    What,
    Contagion
  }
}
</script>

<style>

</style>
