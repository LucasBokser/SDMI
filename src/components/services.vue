<template>
  <v-container>
    <v-row>
      <v-col align="center">
        <h1 class="h">
          <v-icon color="indigo lighten-3" class="mr-2"></v-icon>
          Nos expertises
        </h1>
        <br>
        <!--    <hr style="border:#82CF1F solid 1px;" width="290px">-->
        <h3>DANS LA RÉNOVATION DE L'HABITAT pour votre confort et bien être </h3>
        <v-divider></v-divider>
        <br>
      </v-col>
    </v-row>


<h3 class="center">Plomberie générale</h3>
    <br>
    <b-carousel
        id="carousel-1"
        v-model="slide"
        :interval="4000"
        controls
        indicators
        background="#ababab"
        img-width="1024"
        img-height="480"
        style="text-shadow: 1px 1px 2px #333;"

    > <b-carousel-slide
        caption="Installation de Chaudière"
        text="Spécialiste des installation de chaudière Gaz et Electrique"
        img-src="https://www.prix-travaux.net/wp-content/uploads/2017/03/chaudiere-gaz-1024x682.jpg"
    ></b-carousel-slide>

    <b-carousel-slide
        caption="Plancher Chauffant"
        text="Plancher Chauffant Basse Température avec jonction pompe à chaleur ou chaudière gaz."
        img-src="https://forbo.azureedge.net/forboimages/623281/Plancher-chauffant-forbo.jpg"
    ></b-carousel-slide>

      <b-carousel-slide

          caption="Alimentation en Eau"
          text="Alimentation générale en eau, réfection et mise à jour de nouveaux points de livraison eau chaude et froide"
          img-src="https://renovation-sdmi.weebly.com/uploads/8/8/1/8/88183692/pc1_orig.jpg"
          style=" height: 650px"
      ></b-carousel-slide>
    </b-carousel>
    <br>
    <h3 class="center">Salle de bains</h3>
    <br>
    <b-carousel
        id="carousel-1"
        v-model="slide"
        :interval="4000"
        controls
        indicators
        background="#ababab"
        img-width="1024"
        img-height="480"
        style="text-shadow: 1px 1px 2px #333;"
    > <b-carousel-slide
        caption="Salle de Bain classique carrelée"

        img-src="https://www.novoceram.fr/wp-content/uploads/sites/2/2021/03/salle-de-bain-gres-mur.jpg"
    ></b-carousel-slide>
      <b-carousel-slide
          caption="Bac à douche fait sur mesure en béton ciré"
          img-src="https://lh3.googleusercontent.com/vqnMxK0fF3Q5pmFUJg-lac4yBO4dsuR2VTj8yE0xZMbxn_5wl8M8dgtwmFI7w1u3I6cbKiUXHNPeS3SbT2G5xQ9gnukFXwhKfEcbGjLzpqLGleI"
      ></b-carousel-slide>

    </b-carousel>

    <br>
    <h3 class="center">Sauna & Hamman</h3>
    <br>
    <b-carousel
        id="carousel-1"
        v-model="slide"
        :interval="4000"
        controls
        indicators
        background="#ababab"
        img-width="1024"
        img-height="480"
        style="text-shadow: 1px 1px 2px #333;"

    > <b-carousel-slide
        caption="Nous Sommes spécialisé dans l'implantation et la construction de Sauna ou Hammam chez le particulier "
        img-src="https://blog.piscines-hydrosud.fr/wp-content/uploads/2010/12/la-difference-hammam-sauna-mise-en-avant.jpg"
    ></b-carousel-slide>

      <b-carousel-slide
          caption="Nous Sommes spécialisé dans l'implantation et la construction de Sauna ou Hammam chez le particulier "
          img-src="https://le-rochelois.fr/files/albums/album_50771.jpg"
      ></b-carousel-slide>

      <b-carousel-slide
          caption="Nous Sommes spécialisé dans l'implantation et la construction de Sauna ou Hammam chez le particulier "
          img-src="https://www.refugedelatraye.com/thmb/fixe/1920/1080/medias_upload/moxie/SPA/Sauna_Hammam.jpg"
      ></b-carousel-slide>
    </b-carousel>
  </v-container>

</template>

<script>

export default {
  // data() {
  //   return {
  //     slide: 0,
  //     sliding: null
  //   }
  // },
  // methods: {
  //   onSlideStart(slide) {
  //     this.sliding = true
  //   },
  //   onSlideEnd(slide) {
  //     this.sliding = false
  //   }
  // }
}

</script>
<style>
.center {
text-align: center;
  justify-content: center;
}
@media (min-width: 1200px) {

}

@media (max-width: 350px) {

  img {
    content: "\A";
  }
}

.position {
  margin: 40px;
}

.font {
  font-size: 110%;

}

.v-avatar {
  width: 88px;
}

.item {
  padding-bottom: 80px;
}

.ss {
  font-size: 0.95rem !important;
}

.caption {
  padding-top: 5px;
  display: flex;
}

.btnn {
  background-color: rgb(230, 158, 64) !important;
  border-radius: 5px;
  padding: 17px;
  color: white;
  font-weight: bold;
  font-size: medium;
  margin-left: 110px;
}

.cc {
  padding-top: 2px;
}

.h {
  font-weight: bold;
}

@media (max-width: 767px) {
  .btnn {
    padding: 10px;
    font-size: 1em;
    margin-left: 60px;
  }

  .position {
    margin: 0;
  }

  @font-face {
    font-family: Cyber;
    src: url("https://assets.codepen.io/605876/Blender-Pro-Bold.otf");
    font-display: swap;
  }

  * {
    box-sizing: border-box;
  }

  body {
    display: flex;
    align-items: center;
    flex-direction: column;
    justify-content: center;
    min-height: 100vh;
    font-family: 'Cyber', sans-serif;
    background: linear-gradient(90deg, #f5ed00 60%, #e6de00 60%), #fff700;
  }

  .cybr-btn {
    --primary: hsl(var(--primary-hue), 85%, calc(var(--primary-lightness, 50) * 1%));
    --shadow-primary: hsl(var(--shadow-primary-hue), 90%, 50%);
    --primary-hue: 0;
    --primary-lightness: 50;
    --color: hsl(0, 0%, 100%);
    --font-size: 26px;
    --shadow-primary-hue: 180;
    font-family: 'Cyber', sans-serif;
    color: var(--color);
    text-transform: uppercase;
    background: var(--primary);
    font-size: var(--font-size);
    outline: transparent;
    letter-spacing: 2px;
    font-weight: 700;
    border: 0;
    min-width: 300px;
    padding: 32px 64px;
    box-shadow: inset -3px 0 0 var(--shadow-primary);
  }
}


</style>