<template>
  <a v-on:click="doSomething">你好世界</a>
</template>

<script>
    export default {
      name: "login",
      methods:{
        async doSomething(){
           console.debug("hello world")
        }
      }
    }








</script>

<style scoped>

</style>
