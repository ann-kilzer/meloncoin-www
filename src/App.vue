<template>
  <div id="app">
    <img src="./assets/melon400.png">
    <MelonCoin msg="THE FUTURE IS FRUIT TOKENS"/>
  </div>
</template>

<script>
import MelonCoin from './components/MelonCoin.vue'

export default {
  name: 'app',
  components: {
    MelonCoin
  }
}
</script>

<style>
@import url('https://fonts.googleapis.com/css?family=Roboto');
#app {
  font-family: 'Roboto', sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
}
</style>
