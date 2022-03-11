<template>
  <div class="firstpage">
  <div class="firstpage">
    <body>
 
     <h1 ><span style="color: #FC0303">Hola</span> <span style="color: #FFBD4A"> Amigo </span></h1>


  <p>Username</p>
  <input class="input" type="text" value="Username">
  <p>Password</p>
  <input class="input" type="text" value="Password">
<br>
<router-link to="list">
 <button class="button sign" type="submit">Let's Resume</button>
</router-link>
 <br>
 <p>Dont have an account yet?Sign Up</p>
<router-link to="list">
 <button class="button log" type="submit">Login with <img src="@/assets/assets/google.png"></button>
</router-link>

    </body>
  </div>
  </div>
</template>

<script>
export default {
  name: 'secondpage',
  props: {
    msg: String
  }
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped src="@/assets/assets/css/main.css"></style>