<template>
  <div id="app">
<!--    <Login :user="user"/>-->
    <Home/>
  </div>
</template>

<script>
// import Login from './view/Login.vue'
import Home from "@/view/Home";

export default {
  name: 'App',
  components: {
    Home,
    // Login
  },
  data () {
    return {
      user: {
        username: "mulan",
        password: '123456'
      }
    }
  }
}
</script>

<style>
body{
  background-color: blanchedalmond;
}
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 0px;
}
</style>
