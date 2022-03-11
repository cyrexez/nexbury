<template>
  <div id="app">
  
    <body>
      <div class="newbody">
       <img class="logo" alt="Vue logo" src="@/assets/assets/nexscrow.png"><br/>
       <img class="agree" alr="cuate logo" src="@/assets/assets/cuate.png">

  <br/>
  <p class="texts">We secure every precious sale or purchase you ever want to make.
Real estate, jewels, crypto, books, groceries, cars, gold and anything that worth so much value to you.</p>
<br>

  <router-link to="/login" > 
  <button  class="button sign" type="submit">Login</button>
  </router-link>
 <br>

 <br>
 <br>
 <router-link to="/signup" > 
 <button class="button log" type="submit">Sign up</button>
   </router-link>
      </div>
    </body>

  </div>
  
</template>

<script>
// @ is an alias to /src
import HelloWorld from '@/components/HelloWorld.vue'

export default {
  name: 'Home',
  components: {
    HelloWorld
  }
}
</script>
<style scoped src="@/assets/assets/css/main.css"></style>
