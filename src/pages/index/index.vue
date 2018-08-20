<template>
<div>
  <h1 @click="goPage0">前往Page0</h1>
  <h1 @click="goPage1">前往Page1</h1>
</div>
</template>

<script>
  export default {
    name: 'index',
    methods: {
      goPage0 () {
        location.assign('page0.html')
      },
      goPage1 () {
        location.assign('page1.html')
      },
    }
  }
</script>

<style scoped>

</style>
