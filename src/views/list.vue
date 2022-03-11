<template>
  <div class="firstpage">
  <div class="firstpage">
  <head>
  <title>Home</title>
 
  </head>

    <body>



      
    <div class="hero">
      <img class="listimage" src="@/assets/assets/list/gold.png">
 <div class="textbox">
      <p class="text">Gold & Diamonds</p>
      <div class="seemore">
<p>see more</p>
</div>
 </div>
    </div>


      <div class="hero">
      <img class="listimage" src="@/assets/assets/list/estate.png">
 <div class="textbox">
      <p class="text">Real Estate</p>
      <div class="seemore">
<p>see more</p>
</div>
 </div>
    </div>

  <div class="hero">
      <img class="listimage" src="@/assets/assets/list/bitcoin.png">
 <div class="textbox">
      <p class="text">Cryptocurrencies</p>
      <div class="seemore">
<p>see more</p>
</div>
 </div>
    </div>


      <div class="hero">
      <img class="listimage" src="@/assets/assets/list/vehicles.png">
 <div class="textbox">
      <p class="text">Vehicles</p>
      <div class="seemore">
<p>see more</p>
</div>
 </div>
    </div>


<router-link to="listtwo">
  <p>next</p>
</router-link>

    </body>
  </div>
  </div>
</template>
<style scoped src="@/assets/assets/css/main.css"></style>

<script>

export default {
  name: 'secondpage',
  props: {
    msg: String
  }
}
</script>
