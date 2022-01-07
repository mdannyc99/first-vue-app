<template>
  <div id="app">
    <img alt="Vue logo" src="./assets/logo.png">
    <HelloWorld msg="Welcome to Your Vue.js App"/>
    <myComponent></myComponent>
  </div>
</template>

<script>
import HelloWorld from './components/HelloWorld.vue'
import myComponent from './components/myComponent.vue'

export default {
  name: 'App',
  components: {
    HelloWorld,
    myComponent
  }
}
</script>

<style>
/*
manual css
*/

@import './assets/css/style.css';
</style>
