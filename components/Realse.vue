<template>
<div class="container">
    <h1>RELEASES</h1>
  <v-row>
    <v-col
      
      cols="4"
      sm="3"
    >
      <v-img class="two" height="300"
        src="https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcRBq_asma9WAKJTyFWIW_J6Ja8qze3s4yuEQg&usqp=CAU"
        gradient="to top right, rgba(100,115,201,.33), rgba(25,32,72,.7)"
      ></v-img>
      <br>
      <h5>LOOK TO THE SKY</h5>
    </v-col>

    <v-col
      cols="4"
      sm="3"
    >
      <v-img   class="two" height="300"
src="data:image/jpeg;base64,/9j/4AAQSkZJRgABAQAAAQABAAD/2wCEAAkGBxMTEhUTEhMWFhUXGB0YGBgYGBgaFxgaFxcYFxoYGBcYHSggGBolHRoXIjEhJSkrLi4uFx8zODMtNygtLisBCgoKDg0OFw8QFysdHR0tLSstKystLS0rLS0rLS0rLS0tLS0tLS0tLS0rLS0tLSsrLS0tLS0tLS0tLS0tLS0tK//AABEIALEBHAMBIgACEQEDEQH/xAAcAAACAwEBAQEAAAAAAAAAAAABAgADBAUGBwj/xAA/EAABAwEFBAkDAgMHBQEAAAABAAIR8AMEITFBElFxkQVhgaGxwdHh8QYTIgcyI4KyM0JSYnKSolNjg8LDFP/EABgBAQEBAQEAAAAAAAAAAAAAAAABAgQD/8QAHREBAQEBAAMBAQEAAAAAAAAAAAECEQMhQTEyEv/aAAwDAQACEQMRAD8A+UQmARAqE2yoqBENQhM1AYqqwVwCRtVWasmq7kECjard1aozVaqNr4QNiMTvrtKjBU7sPIIsms8cMN5TNFeXKOSB2jsr4KeOI8sfI+KVg518clYYw0G/unyMKKSOv26vMJbS02QTp5dVYK1oGQHOfAY9uC5PTN6e1zWtjETi0eBQZb1enOMZDcqNoruXH6avFuWnYO07SCMN4ldq7/p1f/8AowN4cz1WbuRuYrxBa5D7bnZL2l/+gb41u06ycYzIcCRGuyM1xLxcXNcYGkRiI7Ck3KXFjH0VfYOw7XIrsl9Bcc3DHDPUdYXWY38ez2g9S1+scHIYnhBFBV2mVRHkNwTluXse4ZlQiMe3fB6956kRQDjXDHkFJrWskX8vL1MqBAsVVYJSExSkVWioSVKqs05FE1CWECmvdKarh4piKKBqu9AhquamtVv5I1Vaot41WKAFJVbk7qrckIQCEhCdL2BAwFYJwlArBO01WSBlCK9VAht41RQXNGCYCarkkaa9N48E7TW+upBC1HZqsSjPXXbioDU+iCbNbvRWNb5VG7qS+lRuTh3HzOHh1qB2Hq34adcmtFGsnE88O7dx1UY2ASeqd0acY3dYR2699/XogLcN3fPrzT9D3NtpfGbQkNAMaTJiUoA+J+StP09bts71tPc1rdkYkgVks7/mt+P+p19m6LaCBhiMl3bHJcTom3sy3aY4O4GVl6W+trvdzsEPe7/KPxHErky69OxeBBXzT9QrkAdsCHHUa+q9XZ/VrLTH7ZjeMY7NVi+qbg282Jh0YEtIy7QpLynOx8jNsYMkdZ4J7s6WgisTqstzuFtav+0xhc6Y/wAojMudk1oGJJXQsbi6yaGuLXZ/kw7THSTi1wzC7Jxy6l51WTjHp/6iVByj03acU5A49Un0SECs+XqtPMjsdMK7vFCK141uTEivH3KXaxqD1Aa+cIFLNajeNw60uzVZ9q0OeI1M9/XWAVJPXWvHiUFZn49lMetMa3eiUVp3qhSkNVqnQJQIUURVb0CgRKnKVAhQ5dqYoHkgcJgUoTIC5BqDiiKrmgZqdjt6RMEFwd1zXWEZr4VbVaCgja+FYBGIQaU7d+PtWHYoLWxyxjsxHiOSrwxHed2nZGm9Q0a7OSDjlXWD4oLRnieY/q9Fmvl2c9w2WzhBEZCRjsjKFa09WNZda6f0/fRZWrdqIOHVp6Zqa9TrWJ3Ujtfp50NeLtfLIutD9m02hs5T+JLZbWS930h9JWNvaOeWy6Zg4sw3tXBvfTl3u9vdrS3cQIeWxlMNAnsJXe6G6e+64BjLRhOILwNhzYwIc0nPcYOK5bq327JnnqEuf0FdxaG1cxoJO1DJwOOAk/i2STAW3pyzYxga0Ybl1LzfTs5QdQvL9M3jA74J7lnd6uMuT9JfTzptHAsNm60Jex0w5rDLQYOpP/ECF5v60t2G9OawAizAbgP70lxiCN4HNdIdKWzLk/7LATtHae50BuJgREuOsSBiM14lrpEk7RkydSd85SceC9vHO3rx82uT/Kx+kjD+bzMKtzh8RpwwQgbhvNaD5QFVvXu5lbwmAwrjXBCFBXOuaBTVbp01lI416+iLt9Vj3IV1/KoBqtEtVvUr49VECkoE14BElCJyrT05oAaqs0C6vhR1evmgUAlKUa80pOCCFLKmJShBa0+ycJITBBEYUrxRiuaA1XemFVWamzpVYpwEAaK3K5g5pYUFV4ILWpmGq64Vcb6CZg31iB5IGiq4hE48fcY96DRur9qgyzr8VAWjqqs+SF6adkkZjHrwjP00TONenj2qOZhnxz5jeg6F3txeTYutGueGQGta2ZIicYgcSvd3O6WjoLbC2YBMA2lnIziATECepfOOiLwbMmz2i0Al4g6HTDCcF7r6WvAYDaWtrgdJ46kmVzbnHd49dj0VztrZjzZ25kRIykHUSM8wub05a7Ic7TfuA8Vl+ovqAMLC14LcSceVUPAdM/UNpenGzYSGbUuO4YCJ6/NYzi1dbmV976WcbEtbgzaL/wDU4gNHZhI48Fz7JkACt/JNeSA0AZT3ASoyTn2BdWZyOPV7fZjW/wCfVDZ6vavBEtx756scUrmrTCvsr2KBFV2Kwtrl5ylgV/KgrdVdqUCvfvKeK5JNyoUhKnqt6BqvFApxrfXclqu5M4Jd6BZquxA8arFEoFArkCjKBKBUqaEpVRbKaUgCYIpwdUwr0VbVYCoHCZqQFNNe6CwcFGlKDWKLa9EFk13T6IjyrkEnPxk6fCIqvFA8zjrPv4wEHVXYOaMwKreeSV7sa105YIGmq0QJqstMUhd7IB1RNdqCm/uGwTls5EeHCViu/TFqRshxCnTdqYDd+J7MB58lzrk+HcU5OLLeutZ3W2tnBskk4L1HSnRTLpZ2VkIL3AveddzRwJ2v9qX6atA1zSRiTCXp29m1vD3EiAdgbgG4cpk9q8e91z5HvZM579rmW2LmjiefwtAbhGqzWLw57iMshwC2ExwXo8FQQca4a8Ezjv7kChxXXd7ygeFaDwToHLOqx5KoqIrh8d6SMlY44V1eQCqKokV7+aleldqiUmq1QRyqrwVhSg76rzQKUhTOCUIgISiQggBQHYiUIQMKzRAQKYCqyVVITtShMAoHmvX0RASphVaIGTgIApggiYTVZJJRDkBe6u+PVISgXV7Vmlc5BNpJaWkAnOFCRVeCoLNs44hBnddy4FxzOK9j0T+k1/ebN7rEtY5ofO0zUTGztSDpiFPpXor714sbOJl20eDceUgL9KNAa0bgI5BZ1q/jU9PhnT3QDrhYG3dZu/hw4y0gSTstkxkXEBfKLa+vtHfkcNwy916r646ede73a2u1+DiQB/2mn8AewB0f4iSvK2NgZnITyTx4/wAxfJu6dzoxuC1OclujSGmRjuTDejKQn2TuTNCdsRXjWaKpdZqp7TXutDscTXBZS8mYwHskRUXJCrSxVwtIHchpXijFfCEIESkVVYJyKrJLCBIUhFCq9EClBMUpCAOSxWaJCVEOKyRBSsKcFVTBMCkCIKgc70ZQBQCC1qaVUCnQEkYKHw+SkJUFd3qOSCOqqxSONVqo4pHOryQBxWq5WP5Y5LKzErqXNsNLlKR9E/SW5bVu+2IyhjeRc7u2Oa919cdOiy6PvD2khxDrJpyIc532zykn+Vcv9PujvtXawwhzgbV3/kmP+LWLzP649LHZu93Bz2rV39DP/pyXnPdar5NZN2nzHwMq6lvN1GcngIg8cOGSo6PZP5b/AA0W5oxXpaix4wAAxKS0ER7p2GSTuVducWneoNFmQB1KEVoqBaY8MM1NpOBrSThklY3DBNtJdqUFDj6pCa5p3qtu5WIBQqoRISEqgyq3JiEhQCVJQKkogFKmSuQAoc1ChKBmpkiKqnCYOS1Xei1A1VyRyQquaaFBCmQIUlBCkJrn7IoGu/0VQpNVwSvNV1yUXiuareK5hBfdGya5rq3q0DG4jAYmM88YWboqxgSV6b6J6LF5vjbN4BbsvLpyI2C3HtcFi1qPqH0r0taW1rbWTmsY+zsmEMaSQNsN/AvnEtaGzgP3jAafIP1O6RF46QtA0y1kWQPVZ4O/5l/cvc3u5u6Hsr3bG1+4602bO7vdH3C9zHF73QP7suI/0iV8iu+Li7lw0WcT6tbrAQIVtn4KtpwVgGC2iwNwVVvm3irZr3Wa0f8AkoFeYJHHxVtnlJrrVVo3891eyvbZHVUEycBkj5mvNAGMs07XCIUGe04V5KqsVfbnALOVYAQlhM/woygQqispSmIQIRCFCUa8EK8EAKWUUEAJUDkClcUDpglArFMAqophVVkhXmjNVWKBxVckUKqtEVAyROElVuQAqE1XaoarchVdviqhSmutlLt8CfSupI41XNauix+Tp/w+enPvUqxuBhoXtf0nIF4tXnMWeyP5nY/0rw1rance5behenjdvvEEh5s/w6iSfyPASexYs9NR1P1c6f8A/wBF6+wwyyxlmBwLjH3D2QG9hXlWMiFTcLPbcXuzJ1zjz91ptf3LXOekWAKycAKhUueBgZ9Ov3VwZodPBA7T2LPajGdFeTA031yWV5Gs8igsefyHDyVzHAzlPwqSf2zoSO5XNu4iZ61Ba5iQuisPcqF2ESknqQLaZLJK2HesI/cVYUxKEolAlVCk7kpqqyTSlcUQpNV2JCnIqqwSSgUhSVCEEAJUgKFKUDhMClbWSYVWiqmRFeqWERXygcBMEspqreoCEsV7ImqKCBXJSUSUpVQC6qrNW9Gv/M/6T4hZ3p7g78+wpfwdK0Wc3eXGcjBMEDADIEgxromt7TVJcHS2es+JWWmk3d4xDoG4gHvwlVNEkrXJjGsgs13xLggrvFicwOsEEYc1pu9mQPTyRIrt0TWJ64ToYZHgs8YELSDieBz8FndZ4TrqgFs3Dt8ldd3AtglZ3EAcvFWWQCC77A0U2ITjdKjiJzreoK5wxrNYR+5y3PMLntzd2Kwpia+UqJQVQqChQRAJSolBApKEopTWaCJSUarcggYGsEwSCq0Tg1WqoYFQVVaJQUaqtEDgppSAogopxWaBKEooFhK4Kw0K1SONd/uiKnHBLdHfxBwKLzVViq7q7+KOB8EG2+PhpTdEO/ht7fFUdI/tOKs6Kd/CbxPip8V0tFjsDD1cy2AzI4SJ4rPZZz1+iithIy1S2Lo81Ve7SHVgnZaY4SR1iCiL35is1Xonfoqt6KqtcuPrKX7nNF247471os7EDREVWVo/ctIfh+SPwltJhRVNs9ZbM58fTNPalIw4dq0lOaHsEhRSyiASgVECghSFMSlJQAlKUSgSgEobSBQVF2g4HwUdXcioimOvDySmu9FREEevkj7+KiiKbf2+Sm6tCiogTd2JHeQRURFLq7lXcf7XsP8ASoog0dKfsT9Hf2P+7yUUU+L9ZR+7tXQuyKiUJ0jrwarrn/dUUVv4Ng14+qqfXJRRZVmvmR4+i2NyHBRRKLrX18lW/Xh5oqKQYHV3KrTmootIJ14BIooiAo5RRADXeoa/2lRRBX7JVFFQEAoog//Z"
      gradient="to top right, rgba(100,115,201,.33), rgba(25,32,72,.7)">
       
      </v-img>
      <br>
      <h5>DOLLER MOGNA NFC</h5>
    </v-col>

    <v-col
    
      cols="4"
      sm="3"
    >
      <v-img class="two" height="300" src="https://images.unsplash.com/photo-1519085360753-af0119f7cbe7?ixid=MnwxMjA3fDB8MHxzZWFyY2h8Nnx8bWVufGVufDB8fDB8fA%3D%3D&ixlib=rb-1.2.1&w=1000&q=80"
      gradient="to top right, rgba(100,115,201,.33), rgba(25,32,72,.7)">
        
      </v-img>
      <br>
      <h5>REALSES#2</h5>

    </v-col>

    <v-col
    
      cols="4"
      sm="3"
    >
      <v-img class="two" height="300" src="https://images.pexels.com/photos/842811/pexels-photo-842811.jpeg?auto=compress&cs=tinysrgb&dpr=1&w=500"
      gradient="to top right, rgba(100,115,201,.33), rgba(25,32,72,.7)">
        
      </v-img>
      <br>
      <h5>AWAKEN THE HERO</h5>

      
    </v-col>
  </v-row>
</div>
</template>
<script>
export default {

}
</script>

<style scoped>
div{
  height:500px;
    background-color: black;
    color:white
}
.two{
  margin:9px 3px;
    border-radius: 10px;
    
    width:100%;
    height:100%;
    top:0;
    left:0;
   
}

.two:hover{
    transform:scale(1.1);
    z-index:1;
}

h1,h5{
    text-align: center;
    
}
/*.bottom-gradient {
    background-image: linear-gradient(to top, rgba(0, 0, 0, 0.4) 0%, transparent 72px);
  }

  .repeating-gradient {
    background-image: repeating-linear-gradient(-45deg,
                        rgba(255,0,0,.25),
                        rgba(255,0,0,.25) 5px,
                        rgba(0,0,255,.25) 5px,
                        rgba(0,0,255,.25) 10px
                      );
  }*/
</style>