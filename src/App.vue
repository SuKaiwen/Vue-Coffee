<template>
  <Navbar />
  <Landing />
  <AboutUs />
  <Ingredients />
  <OurCoffees />
</template>

<script>
import Landing from './components/Landing.vue'
import Navbar from './components/Navbar.vue'
import AboutUs from './components/AboutUs.vue'
import Ingredients from './components/Ingredients.vue'
import OurCoffees from './components/OurCoffees.vue'

export default {
  name: 'App',
  components: {
    Landing,
    Navbar,
    AboutUs,
    Ingredients,
    OurCoffees
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
}


</style>
