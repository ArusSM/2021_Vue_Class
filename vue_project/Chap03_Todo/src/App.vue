<template>
  <div>
    <!-- <img alt="Vue logo" src="./assets/logo.png">
    <HelloWorld msg="Welcome to Your Vue.js App"/> -->
    <TodoTemplate></TodoTemplate>
  </div>
</template>

<script>
// import HelloWorld from './components/HelloWorld.vue'
import TodoTemplate from './components/TodoTemplate.vue'

export default {
  name: 'App',
  components: {
    // HelloWorld
    TodoTemplate
  }
}
</script>

<style>
/* #app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
} */
</style>
