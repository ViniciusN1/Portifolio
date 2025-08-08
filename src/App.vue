<template>
  <div id="app">
    <div style="margin-top: 80px;">
      <homePortf />
     
    </div>
  </div>
</template>

<script>
import homePortf from './components/homePortf.vue';

export default {
  name: 'App',
  components: {
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
