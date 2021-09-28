<template>
  <div class="container">
      <h1>MERCH</h1>


<v-row>
<v-col
v-for="card2 in cards" :key="card2"
      cols="6"
      sm="4"
      align="center"
      
    >
     <v-hover v-slot="{ hover }" >
    <v-card flat
    class="pa-6"
   
    :elevation="hover ? 12 : 0"
  >
 
   <v-img width="300" height="300" :src="card2.src"></v-img>
   <h4>{{card2.title}}</h4>
    <p>{{card2.subtitle}}</p><span><v-icon x-large>{{card2.icon}}</v-icon></span>
  </v-card>
     </v-hover>
</v-col>
</v-row>
</div>
</template>


<script>
export default {
  data() {
    return {
      cards: [
        {
          src:"https://www.seekpng.com/png/detail/217-2172983_unisex-t-shirt-purple-front-300px-x-350px.png",
          icon:"mdi-cart-variant",
          title: 'Shirt',
          subtitle:
            '$39.00',
        },
        {
          src:"https://runescape.wiki/images/thumb/9/91/RuneScape_Evolution_T-Shirt_Competition_image.gif/300px-RuneScape_Evolution_T-Shirt_Competition_image.gif?9c6d5",
          icon:"mdi-cart-variant",
          title: 'White Shirt',
          subtitle:
            '$39.00',
        },
        {
          src:"https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcSRmMfvkMXDF7oKyIKxsbAC7wj_ws8jRyleLlzXfEo1ncFXXAQqwmHxHQpgk2eHe7vsf80&usqp=CAU",
          icon:"mdi-cart-variant",
          title: 'Blue Shirt',
          subtitle:
            '$39.00',
        },
      ],
    }
  },
}
</script>

<style scoped>
h1{
    font-size: 35px;
    margin-top: 10%;
  text-align: center;
}
p {
  margin-top: 5%;
  text-align: center;
  font-size: 20px;
}
</style>

  </div>
</template>


