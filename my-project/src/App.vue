<template>
  <div id="app">
    <my-header></my-header>
    <router-view></router-view>
    <my-menu></my-menu>
  </div>
</template>

<script>
import header from "./components/header";
import menu from "./components/menu";

export default {
  name: 'app',
  components:{
    "my-header":header,
    "my-menu":menu
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
