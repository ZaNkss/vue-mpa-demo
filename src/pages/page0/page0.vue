<template>
  <div>
  <h1>Page0</h1>
  <h1 @click="goIndex">返回主页</h1>
</div>
</template>

<script>
  export default {
    name: 'page0',
    methods: {
      goIndex () {
        location.assign('index.html')
      }
    }
  }
</script>

<style scoped>

</style>
