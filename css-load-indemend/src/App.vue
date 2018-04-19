<template>
  <div id="app">
    <img src="./assets/logo.png">
    <HelloWorld/>
    <md-button>HelloWorld</md-button>
  </div>
</template>

<script>
import HelloWorld from './components/HelloWorld'
// import { Button } from 'mand-mobile'
export default {
  name: 'App',
  components: {
    HelloWorld,
    // Button,
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
