<template>
  <div id="app">
    <header-import/>
      <img src="./assets/logo.png">
      <hello-world/>
    <footer-import/>
  </div>
</template>

<script>
import HelloWorld from './components/HelloWorld'
import HeaderImport from './components/Header'
import FooterImport from './components/Footer'

export default {
  components: {
    HelloWorld,
    HeaderImport,
    FooterImport
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
