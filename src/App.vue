<template>
  <div id="app">
    <img alt="Vue logo" src="./assets/logo.png" />
    <h1>8084</h1>
    <HelloWorld></HelloWorld>
  </div>
</template>

<script>
import HelloWorld from 'module-c/src/components/HelloWorld'
export default {
  name: "App",
  components: {
    HelloWorld
  },
};
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
