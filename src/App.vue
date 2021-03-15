<template>
  <img alt="Vue logo" src="./assets/logo.png">
  <HelloWorld msg="Welcome to Your Vue.js App"/>
  <Buster msg="pup" />
</template>

<script>
import HelloWorld from './components/HelloWorld.vue';
import Buster from '@/components/Buster';

export default {
  name: 'App',
  components: {
    HelloWorld,
    Buster
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
</style>
