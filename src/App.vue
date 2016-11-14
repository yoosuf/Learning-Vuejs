<template>
  <div id="app">
    <!-- <hello></hello> -->
    <products />
  </div>
</template>

<script>
// import Hello from './components/Hello'
import Products from './components/Products'

export default {
  name: 'app',
  components: {
    // Hello
    Products
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
