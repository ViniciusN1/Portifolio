<template>
  <div id="app">
    <AppNavbar />
    
    <div style="margin-top: 80px;">
      <homePortf />
     
    </div>
  </div>
</template>

<script>
import AppNavbar from './components/AppNavbar.vue';
import homePortf from './components/homePortf.vue';

export default {
  name: 'App',
  components: {
    AppNavbar,
    homePortf
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
