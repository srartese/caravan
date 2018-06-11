<template>
  <div id="app">
    <Title />
    <SignUp />
    <SignIn />
  </div>
</template>

<script>
import Title from './components/Title.vue'
import SignUp from './components/SignUp.vue'
import SignIn from './components/SignIn.vue'

export default {
  name: 'app',
  components: {
    Title,
    SignUp,
    SignIn
  }
}
</script>

<style>
#app {
  font-family: 'Avenir', Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  margin-top: 60px;
}
</style>
