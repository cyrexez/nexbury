<template>
  <div class="email">
  <div class="email">
  <head>
  <title>Email</title>
  </head>
    <body>
    
     <h1><span style="color: #FC0303">Email</span> <span style="color: #FFBD4A"> Verification</span> </h1>
<br>
<br>
<br>
<p>Code sent to gab****tus@gmail.com</p>
<br>
<div class="inputt">
  <p>Email verification code <div class="seemore"> see more</div> </p>
</div>
  
<br>
<br>
<br>
<br>
<router-link to="emailsubmit">
 <button class="button sign" type="submit">Submit</button>
</router-link>


    
    </body>
  </div>
  </div>
</template>
<style scoped src="@/assets/assets/css/main.css"></style>
<style scoped >
</style>

<script>
export default {
  name: 'secondpage',
  props: {
    msg: String
  }
}
</script>
