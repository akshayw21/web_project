<template>
<div class="container">
  <v-row>
    <v-col
      
      v-for="n in 9"
      :key="n"
      class="d-flex child-flex overlay"
      cols="4"
    >
      <v-img 
      width="500"
      height="300"
        :src="`https://picsum.photos/500/300?image=${n * 5 + 10}`"
        :lazy-src="`https://picsum.photos/10/6?image=${n * 5 + 10}`"
        aspect-ratio="1"
        class="grey lighten-2"
      >
        <template v-slot:placeholder>
          <v-row
            class="fill-height ma-0"
            align="center"
            justify="center"
          >
            <v-progress-circular
              indeterminate
              color="grey lighten-5"
            ></v-progress-circular>
          </v-row>
        </template>
      </v-img>
    </v-col>
  </v-row>
  </div>
</template>


<style scoped>
div{
    margin-top: 20px;
}

/*.overlay{
  margin:9px 3px;
    border-radius: 10px;
    
    width:100%;
    height:100%;
    top:0;
    left:0;
    opacity: 0;
   
}*/
.gray{
    opacity:1;
    display:block;
    width:100%;
    height:auto;
    transition:.5s ease;
}

.overlay:hover{
    opacity: 0.5;
    /*transform:scale(1.1);
    z-index:1;*/
}


</style>