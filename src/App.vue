<template>
  <div id="app">
    <img alt="Vue logo" src="./assets/logo.png" />
    <HelloWorld msg="Welcome to Your Vue.js App" />
    <Header />
    <label class="form__label">Name</label
    >

    <DialogContainer />



  </div>
</template>

<script>
import HelloWorld from './components/HelloWorld.vue'
import Header from './components/Header.vue'
import DialogContainer from './components/DialogContainer.vue'


export default {
  name: 'App',
  data() {
    return {
      name: '',
      age: 0
    }
  },

  components: {
    HelloWorld,
    Header,
    DialogContainer
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
