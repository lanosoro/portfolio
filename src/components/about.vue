<template>
<div class="about-main">
      <section id="about">
     <div class="container">
         <div class="content-sect">
             <div class="title" style="text-align:left">
                 <h1>About Us</h1>
             </div>
             <div class="content" data-aos="zoom-out" data-aos-duration="1550">
                 <p style="text-align:left" >Medilab & Allied 
                    Products K Ltd is a 
                    Kenyan company, 
                    which is committed 
                    to providing Medical
                    and Research 
                    Reagents and 
                    Consumables, Water 
                    treatment chemicals, 
                    Cooling 
                    Tower/Boiler/Chiller
                    chemicals and
                    Condition Monitoring 
                    reagents/Sensors.</p>
                    <div class="button" data-aos="zoom-in" data-aos-duration="1550" style="text-align:center">
                        <a href="#"  > Read more </a>
                    </div>
                    <div class="social">
                
                    </div>
                  
             </div>
          
         </div>
              <div class="img-sect">
                        <img id="img" src="../assets/chemlab.jpg" alt="">
                        
                    </div>
     </div>
     
      
  </section>
   <h4 style="position:relative; top:0px;">Our customers from around East Africa</h4> 
  <section class="testimonial">
    
      <div class="wrapper">
          <div class="customers" data-aos="fade-right" data-aos-duration="1500"><img src="../assets/research.jpg" id="img"  alt="" height="80%" width="100%" style="border-radius:10px;">
         <h4 id="h4">
             Research Institution
             </h4></div>
          <div class="customers" data-aos="fade-right">
              <img src="../assets/foodprocessor.jpg" alt=""  id="img" height="180%" width="100%" style="border-radius:10px;"><h4 id="h4">
                  Food processors
                  </h4></div>
          <div class="customers" data-aos="fade-left"><img src="../assets/Hospital.jpg" alt="" height="100%" width="100%" id="img" style="border-radius:10px;"><h4 id="h4"> Hospitals</h4></div>
          <div class="customers" data-aos="fade-left" data-aos-duration="1500"><img src="../assets/powerplant.jpg" alt="" id="img" height="100%" width="100%" style="border-radius:10px;"><h4 id="h4">Powerplants</h4></div>
          
      </div>
  </section>
</div>
</template>

<script>
export default {

}
</script>

<style scoped>
    .container{
        width: 80%;
        padding: 0px;
        margin: auto;
        display: flex;
        gap: 40px;
    }
    .content-sect{
        float: left;
        width: 55%;
    }
    .image-sect{
        float: right;
        width: 40%;
 

    }
    .content-sect .title{
        text-transform: uppercase;
        font-size: 28px;
    }
    .content-sect .content h3{
        margin-top: 20px;
        color: #5d5d55;
        font-size:21px;
    }
    .content-sect .content p{
        margin-top:10px;
        font-size: 18px;
        line-height: 1.5;
    }
    .content-sect .content .button a{
        background: rgb(0, 174, 255);
        padding: 12px 40px;
        text-decoration: none;
        color: aliceblue;
        font-size: 25px;
        letter-spacing: 1.5px;
        margin-top: 200px;
        border-radius: 8px;
        transition: all .5s ease-in-out;
    }
    .content-sect .content .button a:hover{
        background: white;
        color:rgb(0, 174, 255);
        box-shadow: 3px 9px 9px rgba(0, 0, 0, 0.357);
    }
    #img{
       width: 100%;
         height: auto;
    }
    .testimonial{
        position: relative;
        top: 0px;
        height: 50vh;
        align-content: center;
        justify-content: center;
        align-items: center;
        margin-bottom: 100px;
       
    }
    .wrapper{
        display: flex;
        position: relative;
        top: 10px;
        justify-content: space-around;
        list-style: none;
        max-height: 300px;
    }
    .customers{
        height: 250px;
        width: 300px;
        border-radius:10px ;
        
        background:rgb(255, 255, 255);
        box-shadow: 0px 10px 10px rgba(0, 0, 0, 0.124);
        margin-left: 20px;

    }
    .about{
        height: 60vh;
        width: 100vw;
        text-align: center;
        display: flex;
        flex-direction: row;
        position: relative;
        top: -100px;


    }
    .about-img{
        left: 50vw;
        position: absolute;
        top: 30%;
            }
    .about-text{
        padding: 20px;
        top: 20%;
        position: relative;
        margin-right: 400px;
        display: flex;
        flex-flow: row wrap;
        text-align: left;

    
    }
    .about-main{
        align-items: center;
        justify-content: center;
        font-family: 'Comfortaa', cursive;
        display: block;
        
      
    }
    .about-text p{
        font-size: 14px;
        font-weight: 500;
        line-height: 2rem;
    }
    #about{
        height: 100vh;
        width: 100%;
        background: rgb(255, 255, 255);
        margin: auto;
        display: flex;
        flex-direction: column;
        flex-flow: row wrap;
        justify-content: space-evenly;
    }
    span{
        font-size: 2em;
    }
    /* span::after{
        background: none repeat scroll 0 0 transparent;
        display: none;
        content: "";
        display: block;
        height: 3px;
        margin-top: 3px;
        margin-bottom: 20px;
        left: 5%;
        width: 100px;
        position: absolute;
        background: black;
        transition: width 0.3s ease 0s, left 0.3s ease 0s;
        width: 50%;
    } */
   
@media  (max-width:991px) {
    .container{
        width: 80%;
        padding: 0px;
        margin: auto;
        display: flex;
        flex-direction: column-reverse;
        gap: 30px;
    }
    .content-sect{
        float: none;
        width: 100%;
        display: block;
        margin: auto;
    }
    .img-sect{
        float: none;
        width: 100%;

    }
    .customers{
        justify-content: center;
        align-items: center;
        text-align: center;
    }
    .customers #h4{
            font-size: 17px;
            position: relative;
            left: 0px;
            display: flex;
    }
    .about{
        height: 120vh;
        position: relative;
        top: 00px;
        display: flex;
        flex-direction: column;
        width: 100%;
        padding: 20px;
    }
    #about{
        text-align: center;
        height: 100vh;
    }
      .about-text {
        font-size: 1em;
     
        line-height: 1.5rem;
        width: 97%;
    }
        .testimonial{
        position: relative;
        top: -80px;
        
        height: 50vh;
        display:flex ;
        flex-flow: row wrap;
        align-content: center;
        justify-content: center;
        align-items: center;
        margin: 10px;
        overflow-y: auto;
    }
     .customers{
        height: 200px;
        width: 200px;
        background: rgba(0, 0, 0, 0.083);
        box-shadow: 0px 10px 10px rgba(0, 0, 0, 0.124);
        margin-left: 25px;
        position: relative;
        left: 300px;
        margin-right: 10px;
        right: 3 00px;

    }
    .customers::-webkit-scrollbar{
        display: none;
    }
       .wrapper{
        display: flex;
        padding: 20px;
        margin-right: 00px;
        justify-content: space-around;
        list-style: none;
        max-height: 300px;
    }
}
@media  (max-width:491px) {
        .about{
        height: 120vh;
        position: relative;
        top: -100px;
        display: flex;
        flex-direction: column;
        width: 100%;
        padding: 20px;
    }
  img{
    height: 200px;
    width: 100vw;
    
    position: relative;

    }
     .content-sect .content .button a{
        background: rgb(0, 174, 255);
        padding: 12px 20px;
        text-decoration: none;
        color: aliceblue;
        font-size: 15px;
        text-align: center;
        letter-spacing: 1.5px;
        margin-top: 200px;
        border-radius: 8px;
        transition: all .5s ease-in-out;
    }
    .content-sect .title{
        text-transform: uppercase;
        font-size: 18px !important;
        text-align: center;
    }
}
</style>