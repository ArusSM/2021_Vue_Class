<template>
  <div class="card-body">
    <!-- <img alt="Vue logo" src="./assets/logo.png"> -->
    <!-- <HelloWorld msg="Welcome to Your Vue.js App"/> -->
    <h1>Vue Component</h1>
    <A06StyleClass></A06StyleClass>
    <A05Event></A05Event>
    <A04LifeCycle></A04LifeCycle>
    <A03Repeater></A03Repeater>
    <A02Binding></A02Binding> 
    
  </div>  
</template>

<script>
// import HelloWorld from './components/HelloWorld.vue'
  // import Currency from './components/A01.Currency'
  import A02Binding from './components/A02.Binding.vue'
  import A03Repeater from './components/A03.Repeater.vue'
  import A04LifeCycle from './components/A04.LifeCycle.vue'
  import A05Event from './components/A05.Event.vue'
  import A06StyleClass from './components/A06.StyleClass.vue'

export default {
  name: 'App',
  components: {
    // HelloWorld
    A02Binding,
    A03Repeater,
    A04LifeCycle,
    A05Event,
    A06StyleClass,
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
