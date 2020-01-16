<template>
    <div>
        <div class="hero-image">
            <div class="button" style="color:#000;">
            <h2>Naši proizvodi</h2>
            </div>
            <div class="proizvodiBg" style="background-color:white;width:100%;">
                <div class="container">
                    <div class="row">
                        <div class="col-4">
                            <img src="https://via.placeholder.com/250">
                            <div class="button2" style="color:#000;">
                                <router-link to="/vina"><h2>Vina</h2></router-link>
                            </div>
                        </div>
                        <div class="col-4">
                            <img src="https://via.placeholder.com/250">
                            <div class="button2" style="color:#000;">
                                <router-link to="/rakijeilikeri"><h2>Rakije i likeri</h2></router-link>
                            </div>
                        </div>
                        <div class="col-4">
                            <img src="https://via.placeholder.com/250">
                            <div class="button2" style="color:#000;">
                                <router-link to="/marmelade"><h2>Marmelade</h2></router-link>
                            </div>
                           <router-link class="button3" to="/">Natrag</router-link> 
                              
                        </div>
                    </div>
                </div>
            </div>
        </div>  
    </div>
</template>

<style lang="scss" scoped>
.button{
    display:inline-block;
     text-align: left; 
    height: 80px;
    border-radius: 15px;
    width: 18em;
    margin-top: 50px;
      background-color: rgba(214, 248, 62, 0.918);
    font-size: 2em;
    box-shadow: 5px 10px 18px black;
    line-height: 5em;
     padding-top: 20px;
      font-family: 'Playfair Display', serif;
      margin-left:10px;
      
     

  
}
.button2{
    height: 80px;
    text-align: center;
    border-radius: 15px;
    width: 8em;
    margin-top: 50px;
      background-color: rgba(214, 248, 62, 0.918);
    font-size: 2em;
    box-shadow: 5px 10px 18px black;
    padding-top: 20px;
    font-family: 'Playfair Display', serif;
   

}
.hero-image{
    background-image: url("/images/pozadinaNasiProizvodi.png");
    background-position: center bottom;
    background-repeat: no-repeat;
    background-size: cover;
    position: relative;
    text-align: left;

}
.proizvodiBg{
    padding-top: 80px;
}
.button3{
    display:inline-block;
    height: 70px;
    border-radius: 15px;
    text-align: center;
    width: 6em;
    margin-top: 2em;
    background-color: rgba(214, 248, 62, 0.918);
    color: black;
    float:right;
    font-size:2.3em;
    box-shadow: 5px 10px 18px black;
    margin-right:0.1em;
    font-family: 'Playfair Display', serif;
  }
  
    .button2:hover{
        background-color: rgb(206, 255, 92);
    width:240px;
    transition: 2s;}

    
    .button3:hover{
    
    background-color: rgb(206, 255, 92);
    width:260px;
    transition: 2s;}

   

</style>