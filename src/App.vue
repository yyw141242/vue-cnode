<template>
  <div id="app">
    <img src="./assets/logo.png">
    <div id="app">
  {{ message }}
</div>
  </div>
</template>

<script>
export default {
  name: 'app',
  data () {
    return {
      message: 'Hello Vue!'
    }
  },

  lala () {
    var a = 123
    console.log(a)
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
