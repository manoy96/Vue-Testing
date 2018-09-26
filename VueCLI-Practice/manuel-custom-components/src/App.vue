<template>
  <div id="app">
    <my-header></my-header>
    <my-serve-det></my-serve-det>
    <my-servers></my-servers>
    <my-footer></my-footer>
    
  </div>
</template>

<script>
import HelloWorld from './components/HelloWorld.vue'
import Header from './components/Header.vue'
import Footer from './components/Footer.vue'
import ServerDetails from './components/ServerDetails.vue'
import Servers from './components/Servers.vue'

export default {
  name: 'app',
  components: {
    HelloWorld,
    'my-header': Header,
    'my-footer': Footer, 
    'my-serveDet': ServerDetails,
    'my-servers': Servers
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
  margin-top: 60px;
}
</style>
