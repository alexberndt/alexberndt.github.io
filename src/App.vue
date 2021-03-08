<template lang="pug">
#app
  Navbar
  router-view
  Footer
</template>

<script>
  import 'bootstrap'
  import 'bootstrap/dist/css/bootstrap.min.css'

  import Navbar from './components/Navbar.vue';
  import Footer from './components/Footer.vue';

  export default {
  name: 'App',
  components: {
    Navbar,
    Footer
    }
  }
</script>


<style>
#app {
  font-family: 'Avenir', Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
}
#nav {
  padding: 10px;
}
</style>