<template>
  <div class="hello">
    <h1>{{ msg }}</h1>
  </div>
</template>

+<script>
    export default {
      name: 'HelloWorld',
        data () {
          return {
            msg: 'Hello'
        }
        }
    }
    </script>

<style lang="scss" scoped>
  .hello {
    h1,
    h2 {
      color: #42b983;
      font-weight: normal;
    }
  }
</style>