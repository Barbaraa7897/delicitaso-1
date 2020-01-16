<template>
    <div>
        <div class="button" style="color:#000;">
            <h3>Marmelade</h3>
                                
        </div>
        <div class="marmelade" style="width:100%;">
                <div class="container">
                    <div class="row">
                        <div class="col-3">
                           <img src="https://via.placeholder.com/250"> 
                           <img src="https://via.placeholder.com/250"> 
                        </div>
                         <div class="col-3">
                           <img src="https://via.placeholder.com/250">
                           <div class="button1" style="color:#000;">
                            <h6>Marmelada od višnje</h6>
                                
                             </div>
                             <div class="wrap">
                            <div class="button2" style="color:#000;">
                                <h6>Rezerviraj</h6> 
                                <i class="fa fa-thumbs-o-up" aria-hidden="true"></i> 
                                <i class="fa fa-thumbs-o-up" aria-hidden="true"></i>
                            </div>   
                             </div>
                           <img src="https://via.placeholder.com/250"> 
                         </div>
                        <div class="col-3">
                         <img src="https://via.placeholder.com/250">
                         <img src="https://via.placeholder.com/250"> 
                        </div>
                        <div class="col-3">
                            <img src="https://via.placeholder.com/250">
                            <img src="https://via.placeholder.com/250"> 
                         </div>
                    </div>
                </div>
        </div>
        
   </div>
</template>

<style lang="scss" scoped>
.bg-image {
  /* The image used */
  background-image: url("/images/voce.jpg");
  
  /* Add the blur effect */
  filter: blur(8px);
  -webkit-filter: blur(8px);
  
  /* Full height */
  height: 100%; 
  
  /* Center and scale the image nicely */
  background-position: center;
  background-repeat: no-repeat;
  background-size: cover;
}

.button{
    display:left;
    height: 80px;
    border-radius: 15px;
    width: 10em;
    margin-top: 50px;
      background-color: rgba(230, 236, 202, 0.918);
    font-size: 2em;
    box-shadow: 5px 10px 18px black;
    line-height: 80px;
}
 h3 {
      line-height: 80px;
      margin-bottom:100px;
      margin-right:20px;
}
.button1{
    height:50px;
    border-radius: 10px;
    box-shadow: 5px 10px 18px black;
    font-size:1em;
    margin:15px;
    background-color:  rgba(230, 236, 202, 0.918);
}
.button2{
    height:30px;
    border-radius: 20px;
    box-shadow: 5px 10px 18px black;
    font-size:1em;
    margin:15px;
    background-color:  rgba(191, 196, 173, 0.918);
    width: 80px;
    
}
</style>