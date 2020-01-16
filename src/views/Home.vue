<template>
  <div>
    <div class="hero-image">
      <div class="hero-text" style="color:#000;">
        <h1>delicitaso</h1>

        <ul class="homeTopNav" style="display:;">

          <li><router-link class="button1" to="/login">Prijava</router-link></li>
              <li><router-link class="button2" to="/registracija">Registracija</router-link></li>
         
        </ul>
        <ul class="homeNav" style="margin-top:100px;">
            
          <li><router-link class="button" to="/nasiproizvodi">Naši proizvodi</router-link></li>
          <li><router-link class="button" to="/obavijesti">Obavijesti</router-link></li>
          <li><router-link class="button" to="/about">O nama</router-link></li>
        
        </ul>
      </div>
    </div>
  </div>
</template>
<style lang="scss" scoped>
  h1{
    
    text-align: center;
    text-transform: uppercase;
    font-weight: 500;
    font-size: 6em;
    letter-spacing: 0.4em;
    display:inline-block;
    width: 100%;
    text-align: left;
    line-height: 1em;
    font-family: 'Playfair Display', serif;
  }
  .hero-image{
    background-image: url("/images/naslovna2.jpg");
    height: 770px;
    background-position: center;
    background-repeat: no-repeat;
    background-size: cover;
    position: relative;
  }
  .homeTopNav{
    text-decoration:none;
    float:left;
    line-height: 0.1em;
  }
  a{
    text-decoration: none;
    color:black;
    font-weight: 600;
    font-size: 1.5em;
    font-family: 'Playfair Display', serif;
  }
  .topNavMember{
    display:inline-block;
    margin-left: 20px;
  }
  ul{
    list-style: none;
  }
  .button{
    display:inline-block;
    height: 80px;
    border-radius: 15px;
    width: 18em;
    margin-top: 30px;
    background-color:rgb(169, 202, 21);
    font-size: 2em;
    box-shadow: 5px 10px 18px black;
    line-height: 2.5em;
    font-family: 'Playfair Display', serif;
  }
  .button:hover{
    
    background-color: rgb(206, 255, 92);
    width:540px;
    transition: 2s;
  }

  .button1{
display:inline-block;
text-decoration:none;
margin-top:30px;
}

.button2{
display:inline-block;
text-decoration:none;
margin-right: 10em;



}


.homeNav{
  width:100%;
  display:inline-block;
}
</style>