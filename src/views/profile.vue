<template>
  <div class="firstpage">
  <div class="firstpage">
  <head>
  <title>email</title>
  </head>
    <body>
      <div class="newbody">
     <h1 ><span style="color: #FC0303">Add</span> <span style="color: #FFBD4A"> Profile Picture </span></h1>
<p>One more step</p>
<img src="@/assets/assets/circlecenter.png">

<p>Add Profile Picture</p>
  <br>


 <br>
 <br>
 <div>
<input type="checkbox">I agree to the terms of service
</div>
<div>
<input type="checkbox"> I agree to the privacy policy
</div>
<router-link to="changeprofile">
 <button class="button sign" type="submit">Done</button>
</router-link>

      </div>
    </body>
  </div>
  </div>
</template>
<style scoped src="@/assets/assets/css/main.css">
</style>
<style>

</style>

<script>
export default {
  name: 'secondpage',
  props: {
    msg: String
  }
}
</script>
