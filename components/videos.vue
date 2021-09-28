<template>
  <div class="container">
      <h1>LAST VIDEOS</h1>
      <div class="row">
          <div class="col-12 col-lg-6 col-sm-3">
          <video class="mp41" controls width="300" height="250">

    <source src="@/assets/flower.webm">

   
    Sorry, your browser doesn't support embedded videos.
</video>
    </div>
     <div class="col-12 col-lg-6 col-sm-4">
          <video class="mp42" controls width="300" height="250">

    <source src="@/assets/flower.webm">

   
    Sorry, your browser doesn't support embedded videos.
</video>
    </div>

     <div class="col-12 col-lg-6 col-sm-4">
          <video class="mp43" controls width="300" height="250">

    <source src="@/assets/flower.webm">

   
    Sorry, your browser doesn't support embedded videos.
</video>
    </div>
    
      </div>

       <div class="one">
      <v-btn large depressed color="success"> Read More </v-btn>
    </div>
   </div>
   
</template>

<script>
export default {

}
</script>

<style>
.container{
    margin-top:40px;
}
h1{
    text-align: center;
}
.mp42{
    position:relative;
    top:0;
    left:-155px;
}

.mp43{
    position:relative;
    top:-281px;
    left:830px;
}

.one{
  margin-top:5px;
  width:500px;
  position:relative;
  top:-240px;
  left:500px;

}
</style>