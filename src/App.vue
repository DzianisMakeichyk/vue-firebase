<template>
  <div id="app">
    <img src="./assets/logo.png">
    <router-view/>
  </div>
</template>

<script>
export default {
  name: 'app',
    methods: {
      loaders: [
        {
          test: /\.vue$/,
          loader: 'vue'
        },
        {
          test: /\.s[a|c]ss$/,
          loader: 'style!css!sass'
        },
      ]
    },
    vue: {
      loaders: {
      scss: 'style!css!sass'
    }
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
