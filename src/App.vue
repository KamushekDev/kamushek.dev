<template>
  <img alt="My avatar" src="./assets/avatar.png">
  <UnderDevelopment />
</template>

<script>
import UnderDevelopment from './components/UnderDevelopment.vue'

export default {
  name: 'App',
  components: {
    UnderDevelopment
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
