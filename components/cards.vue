<template>
  <div class="container justify-center">
    <div class="row">
      <div class="col-12">
        <v-row>
          <v-col
            v-for="card in cards"
            :key="card"
            cols="6"
            sm="4"
            align="center"
            width="300px"
            height="350px"
          >
            <v-hover v-slot="{ hover }">
              <v-card flat class="pa-6" :elevation="hover ? 12 : 0">
                <v-img :src="card.src"></v-img>
                <h1>{{ card.title }}</h1>

                <p>
                  {{ card.subtitle }}
                </p>
                <p>{{ card.para }}</p>

                <v-btn x-large depressed color="success"> Read More </v-btn>
              </v-card>
            </v-hover>
          </v-col>
        </v-row>
      </div>
    </div>
    <div class="one">
      <v-btn large depressed color="success"> Read More </v-btn>
    </div>
  </div>
</template>

<script>
export default {
  data() {
    return {
      cards: [
        {
          src: 'data:image/jpeg;base64,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',
          title: 'STANDARD POST',
          subtitle: 'April 27,2014',
          para: 'Lorem sit quis in dianissim rhoncus sed.Nisi lorem ut...',
        },
        {
          src: 'https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcQg5dtLdDrYcPa05Tg9kwcEhmflFv100qTuTQ&usqp=CAU',
          title: 'PLAYLIST',
          subtitle: 'April 28,2014',
          para: 'Odio sociis pid urna,mid amet, mauris placerat!Ut scelerisque dianissim rhoncus sed.Nisi lorem..',
        },
        {
          src: 'https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcTSo15PVKKneGlY9P4wQIft0gZqdQVEaU8eehjdnxb0kmuhg86T9Qu0471yt5zrmSiIY30&usqp=CAU',
          title: 'OFFICIAL VIDEO',
          subtitle: 'April 27,2014',
          para: 'Odio sociis pid urna,mid amet, mauris placerat!Ut scelerisque dianissim rhoncus sed.Nisi lorem..',
        },
      ],
    }
  },
}
</script>

<style scoped>
h1 {
  margin-top: 10%;
  text-align: center;
}
p {
  margin-top: 5%;
  text-align: center;
  font-size: 20px;
}
.one{
  margin-top:5px;
  width:500px;
  position:relative;
  top:0px;
  left:500px;

}
</style>
