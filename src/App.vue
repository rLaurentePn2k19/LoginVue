<template>
  <div id="app">
    <Header></Header>
    <AppBody></AppBody>
  </div>
</template>

<script>
// import Form from './components/Form.vue'
import Header from 'components/frame/Header.vue'
import AppBody from 'components/frame/Body.vue'
 
export default {
  name: 'app',
  components: {
    // Form,
    Header,
    AppBody
  }
}
</script>

<style>
/* #app {
  font-family: 'Avenir', Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
} */
</style>
