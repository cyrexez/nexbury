<template>
  <div class="finalprofile">
  <div class="email">
  <head>
  <title>User Profile</title>
  </head>
    <body>
      <div class="">

     <h1 ><span style="color: #FC0303">Sign-</span> <span style="color: #FFBD4A">up</span></h1>

<form>
    <label>Full Name</label><br>
  <input type="text" class="input" value="Gabby lotus" ><br>

   <label>Username</label><br>
  <input class="input" type="text" value="Gabby lotus" ><br>
   <label>Email Address</label><br>
  <input type="text" class="input" value="Gabby lotus" ><br>
   <label>Home Address</label><br>
  <input class="input" type="text" value="Gabby lotus" ><br>
   <label>Phone number</label><br>
  <input class="input" type="text" value="Gabby lotus" ><br>

  </form>
  
<br>
<br>
<router-link to="email">
 <button class="button sign" type="submit">Lets go</button>
</router-link>



      </div>
    </body>
  </div>
  </div>
</template>
<style scoped src="@/assets/assets/css/main.css"></style>
<style scoped>
.alignform{
align-items: left;
justify-content: left;
place-items:left;
margin: auto 0px;

}
  </style>

<script>
export default {
  name: 'secondpage',
  props: {
    msg: String
  }
}
</script>
