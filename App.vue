<template>
  <img alt="头像" src="./assets/zy1.png">
  <HelloWorld msg="姓名：钟悦  学号：441521"/>
</template>

<script>
import HelloWorld from './components/Login.vue'

export default {
  name: 'App',
  components: {
    HelloWorld
  }
}
</script>

<style>
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
}
</style>
