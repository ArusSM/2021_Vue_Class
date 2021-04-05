<template>
  <div class="card-body">
    <!-- <img alt="Vue logo" src="./assets/logo.png"> -->
    <!-- <HelloWorld msg="Welcome to Your Vue.js App"/> -->
    <h1>Vue Component</h1>
    <A02Binding></A02Binding>
    <A03Binding></A03Binding>
    <A04Binding></A04Binding>
    <A05Binding></A05Binding>
  </div>  
</template>

<script>
// import HelloWorld from './components/HelloWorld.vue'
  // import Currency from './components/A01.Currency'
  import A02Binding from './components/A02.Binding.vue'
  import A03Binding from './components/A03.Repeater.vue'
  import A04Binding from './components/A04.LifeCycle.vue'
  import A05Binding from './components/A05.Event.vue'

export default {
  name: 'App',
  components: {
    // HelloWorld
    A02Binding,
    A03Binding,
    A04Binding,
    A05Binding
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
