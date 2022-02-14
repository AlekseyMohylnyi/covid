<template>
  <div id="app">    
    <Header />
    <What />
    <Contagion />
    <Symptomps />
    <Should />
    <Reports />
  </div>
</template>

<script>
import Header from './components/Header.vue'
import What from './components/What.vue'
import Contagion from './components/Contagion.vue'
import Symptomps from './components/Symptomps.vue'
import Should from './components/Should.vue'
import Reports from './components/Reports.vue'

export default {
  name: 'App',
  components: {
    Header,
    What,
    Contagion,
    Symptomps,
    Should,
    Reports
  }
}
</script>

<style>

</style>
