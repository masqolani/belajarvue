<template>
  <div id="main">
    <header-import/>
    <footer-import/>
  </div>
</template>

<script>
import HelloWorld from './components/HelloWorld'
import HeaderImport from './components/Header'
import FooterImport from './components/Footer'
// import DataDua from './components/DataDua'

export default {
  components: {
      HelloWorld,
      HeaderImport,
      FooterImport,
    }
}

</script>

<style>
</style>
