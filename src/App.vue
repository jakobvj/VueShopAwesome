<template>
  <div id="app">
    <img src="./assets/logo.png">
    <h1>{{ msg }}</h1>
    
    <h2>Ecosystem</h2>
    <button @click="calc()">Klik</button>
  </div>
</template>

<script>
export default {
  
  name: 'app',
  data () {
    
    return {
      msg: 'Welcome to Your Vue.js  App'
    }
  },
  methods: {
    calc(){
      alert("!!!!")
    }
  }
}
</script>

<style>
</style>
