<template>

  <div class="view" >
<img src="https://renovation-sdmi.weebly.com/uploads/8/8/1/8/88183692/background-images/1149792874.jpg" style="width: 100%">
    <div class="texte_centrer" style="font-size: larger "><p class="p">
      <FONT size="11">S.D.M.I
        <br>
        SOCIÉTÉ DAUPHINOISE DE MAINTENANCE IMMOBILIERE</FONT></p>
      </div>


  </div>
</template>

<script>
  export default {
    name: 'accueil',

  }
</script>
<style>

.p
{
  text-shadow: #000000 1px 1px, #000000 -1px 1px, #000000 -1px -1px, #000000 1px -1px;

}
.view {
  position: relative;
  text-align: center;
  color: white;
}
.texte_centrer {
  font-family: "Questrial" !important;
  position: absolute;
  top: 50%;
  left: 50%;
  transform: translate(-50%, -50%);


}
video {
  width: 100%;
  height: auto;
}

v-img.back{
  position: absolute;
  width: 100%;
}
nav.bottomNav{
  background-color:rgba(0,0,0,0.4);
  position: absolute;
  width: 100%;
  bottom: -19px;
}

 
/* Large desktop */
@media (min-width: 1200px) {

}

/* Portrait tablet to landscape and desktop */
@media (min-width: 768px) and (max-width: 979px) {

}

/* Landscape phone to portrait tablet */
@media (max-width: 767px) {

}

/* Landscape phones and down */
.center{
  display: block;
  margin-right: auto;
  margin-left: auto;
  width: 100%;
}
</style>
