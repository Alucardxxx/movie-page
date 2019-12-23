<template>
  <div id="app">
    <HelloWorld/>

  </div>
</template>

<script>
import HelloWorld from './movie-page-home.vue'

export default {
  name: 'app',
  components: {
    HelloWorld
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
  font-size: 0px;
  margin:0 auto;
  padding: 0;
}
a{
  
  text-decoration: none;
}
li{
  list-style:none;
}
</style>
