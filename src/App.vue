<template>
  <div id="app">
    <FlipBook />
  </div>
</template>

<script>
import FlipBook from "./components/FlipBook.vue"
export default {
  name: 'App',
  components: {
    FlipBook
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
