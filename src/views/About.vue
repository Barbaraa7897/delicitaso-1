<template>
  <div class="about">
    <div class="hero-image2">
      <div class="aboutNaslov">
        <h2>O nama...</h2>
      </div>
      <div class="aboutSadrzaj">
        <p>
            Obiteljski posao „Delicitaso“ postoji od 1920. godine kada je i kupljen današnji posjed pod vinogradom od grofa Festića. Do današnjih dana, trenutno su prošle 3 generacije stvaranja najkvalitetnijih proizvoda koji okrijepe tijelo i razvesele dušu uz domaće namjernice sa našeg imanja. Naši proizvodi nagrađivani su diljem Hrvatske te i od stane drugih zemalja kao što su Slovenija i Austrija.
Uzgoj naših proizvoda, vinograd te i samo imanje se nalaze u Varaždinskoj županiji, zahvaljujući umjerenoj kontinentalnoj klimi što vlada našim krajevima, vinogradi , voćnjaci i šume su nerijetka pojava, pa su tako i naši proizvodi dobro poznati po svojoj ne zamjenjivoj kvaliteti i paleti okusa.

        </p>
        <router-link class="buttonAbout" to="/">Natrag</router-link>
      </div>
    </div>

  </div>
</template>
<style lang="scss">
  .aboutNaslov{
    line-height: 3em;
    width: 300px;
    height: 80px;
    background-color: rgba(214, 248, 62, 0.918);
    color:black;
    text-align: center;
    font-size:3em;
     font-family: 'Playfair Display', serif;
  }
  .aboutSadrzaj{
    background-color: white;
    display: inline-block;
    margin-left: 300px;
    font-size: 2.3em;

  }
  .hero-image2{
    background-image: url("/images/onama.jpg");
    background-position: center bottom;
    background-repeat: no-repeat;
    background-size: cover;
    position: relative;
    text-align: left;
  }
  .buttonAbout{
    display:inline-block;
    height: 80px;
    border-radius: 15px;
    text-align: center;
    width: 5em;
    margin-top: 35px;
    background-color: rgba(214, 248, 62, 0.918);
    color: black;
    float:right;
    font-family: 'Playfair Display', serif;
  }
  .buttonAbout:hover{
   
    background-color: rgb(206, 255, 92);
    width:200px;
    transition: 2s;}
</style>