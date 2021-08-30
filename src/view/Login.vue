<template>
  <div id='container'>
    <form>
      <label for="username">UserName:</label>
      <input id="username" v-model="user.username" placeholder="Please Enter Your Username!"><br>
      <label for="password">Password:</label>
      <input id="password" v-model="user.password" type="password" placeholder="Please Enter Your Password!"><br>
      <button value="">Submit</button>
    </form>
  </div>
</template>

<script>
export default {
  name: "Login",
  props: ['user'],
  methods: {

  }
}
</script>

<style scoped>
form label{width:80px;height:30px;margin:auto 0px 20px 0px;font-size:18px}
form input{width:200px;height:30px;margin:20px auto 20px 10px;font-size:18px}
form button{width:80px;height:30px;margin:20px auto 20px 10px;font-size: 18px}
</style>
