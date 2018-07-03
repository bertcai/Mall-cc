<template>
  <div class="test">
    this is id:{{$route.params.testId}}
    <br />
    this is name:{{$route.params.testName}}
  </div>
</template>

<script>
export default {
  data () {
    return {
      msg: 'hello vue'
    }
  }
}
</script>

<style scoped>

</style>
