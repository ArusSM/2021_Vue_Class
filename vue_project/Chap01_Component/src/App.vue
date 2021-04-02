<template>
  <div class="card-body">
    <!-- <img alt="Vue logo" src="./assets/logo.png"> -->
    <!-- <HelloWorld msg="Welcome to Your Vue.js App"/> -->
    <h1>Vue Component</h1>
    <A02Binding></A02Binding>
  </div>  
</template>

<script>
// import HelloWorld from './components/HelloWorld.vue'
  // import Currency from './components/A01.Currency'
  import A02Binding from './components/02.Binding.vue'

export default {
  name: 'App',
  components: {
    // HelloWorld
    A02Binding
    // Currency
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
