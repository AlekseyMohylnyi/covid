<template>
  <div id="app">   
    <HeaderNav /> 
    <Header />
    <What />
    <Contagion />
    <Symptomps />
    <Should />
    <Reports />
    <Footer />
  </div>
</template>

<script>
import HeaderNav from './components/HeaderNav.vue'
import Header from './components/Header.vue'
import What from './components/What.vue'
import Contagion from './components/Contagion.vue'
import Symptomps from './components/Symptomps.vue'
import Should from './components/Should.vue'
import Reports from './components/Reports.vue'
import Footer from './components/Footer.vue'

export default {
  name: 'App',
  components: {
    HeaderNav,
    Header,
    What,
    Contagion,
    Symptomps,
    Should,
    Reports,
    Footer
  }
}
</script>

<style>

</style>
