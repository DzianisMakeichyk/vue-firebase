<template>
  <div id="app">
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

<style lang="scss" scoped>

</style>
