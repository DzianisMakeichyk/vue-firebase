<template>
  <div class="hello">
      <Card style="width:320px" dis-hover>
          <div style="text-align:center">
              <h1>{{ msg }}</h1>
          </div>
      </Card>
  </div>
</template>

<script>
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
        position: absolute;
        left: 50%;
        top: 50%;
        transform: translateY(-50%) translateX(-50%);

    }
</style>