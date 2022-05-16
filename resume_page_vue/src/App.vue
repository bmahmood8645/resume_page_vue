<template>
  <div id="app">
  <headerresume/>
  <img src="./assets/profile_picture.jpg">
  </div>
</template>

<script>
import headerresume from './components/rename_header.vue'

export default {
  name: 'app',
  components: {
    headerresume
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
  margin-top: 60px;
}
img{
  border-radius: 50%; 
  height: 200px;
  width: 250px;
  position: absolute;
  top: 0;
  left: 0;
}
</style>
