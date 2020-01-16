<template>
  <div class="obavijesti">
    <div class="hero-image3">
      <div class="obavijestiNaslov">
        <h3>Obavijesti</h3> </div>
         <div class="obavijestiSadrzaj">
        <p>
            Trenutno nema obavijesti.
            </p>
             <router-link class="buttonObavijesti" to="/">Natrag</router-link>
            </div>
        </div>
          </div>
           
        
        </template>
<style lang="scss">
.hero-image3{
    background-image: url("/images/obavijesti.jpg");
    background-position: center ;
    background-repeat: no-repeat;
    background-size: cover;
    position: relative;
    text-align:  left;
    
}
.obavijestiNaslov{
    line-height: 5em;
    width: 300px;
    height: 100px;
    background-color: rgb(255, 255, 255);
    color:black;
    text-align: center;
    border: 2px black solid;
    font-family: 'Playfair Display', serif, bold;

    
    }
    .obavijestiSadrzaj{
    background-color:white;
    display: inline-block;
    font-size: 30px;
     width: 60em;
    height: 320px;
     margin-top:3em;
  
    
    }
    .buttonObavijesti{
    display:inline-block;
    border-radius: 15px;
    text-align: center;
    width: 6em;
    line-height: 2em;
    margin-top: 15em;
    background-color: rgb(255, 255, 255);
    color: black;
    border:black 2px solid;
    margin-left: 44em;
    
  }
  .buttonObavijesti:hover{
    /*tu stoji kićasti stil koji M@Rk0 ne voli a moraće da trpi h3h3h3*/
    background-color: rgb(206, 255, 92);
    width:200px;
    transition: 2s;}
</style>