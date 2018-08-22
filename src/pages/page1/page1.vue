<template>
<div>
  <h1>Page1</h1>
  <h1 @click="goIndex">返回主页</h1>
  <h1> <hello></hello> </h1>
</div>
</template>

<script>
  import hello from "../../components/HelloWorld"
  export default {
    name: 'page1',
    methods: {
      goIndex () {
        location.assign('index.html')
      }
    },
    components:{
      hello
    }
  }
</script>

<style scoped>

</style>
