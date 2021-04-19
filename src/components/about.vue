<template>
<div class="about-main">
      <section id="about">
      <div class="about col-lg-12 col-sm-12 col-md-12">
                    
           <div class="about-text" data-aos="fade-in" data-aos-duration="2000">
               <span>About us</span>
               <p style="padding:20px 0px">
                    Medilab & Allied 
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
            reagents/Sensors.
               </p>
           </div>
           
      </div>
      
  </section>
  
  <section class="testimonial">
     <h1 style="position:relative; top:80px;">Our customers</h1> 
      <div class="wrapper">
          <div class="customers" data-aos="slide-right" data-aos-duration="1500"><h3 id="h3">Research Instituition</h3></div>
          <div class="customers" data-aos="slide-right"><h3 id="h3">Food processors</h3></div>
          <div class="customers" data-aos="slide-left"><h3 id="h3">Hospitals</h3></div>
          <div class="customers" data-aos="slide-left" data-aos-duration="1500"><h3 id="h3">Power plants</h3></div>
          
      </div>
  </section>
</div>
</template>

<script>
export default {

}
</script>

<style scoped>
    .testimonial{
        position: relative;
        top: -80px;
        height: 50vh;
        align-content: center;
        justify-content: center;
        align-items: center;
        margin-bottom: 100px;
       
    }
    .wrapper{
        display: flex;
        position: relative;
        top: 100px;
        justify-content: space-around;
        list-style: none;
        max-height: 300px;
    }
    .customers{
        height: 250px;
        width: 300px;
        border-radius:10px ;
        padding: 30px 20px;
        background: rgba(0, 0, 0, 0.083);
        box-shadow: 0px 10px 10px rgba(0, 0, 0, 0.124);
        margin-left: 20px;

    }
    .about{
        height: 40vh;
        width: 70%;
        text-align: center;
        display: flex;
        flex-direction: row;


    }
    .about-img{
        left: -800px;
        position: fixed;
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
        display: flex;
        flex-flow: column wrap;
    }
    .about-text p{
        font-size: 1.5em;
        font-weight: 500;
        line-height: 2rem;
    }
    #about{
        height: 50vh;
        width: 90%;
        background: rgba(255, 255, 255, 0.207);
        box-shadow: 0 10px 10px rgba(0, 0, 0, 0.337);
        margin: 40px;
    }
    span{
        font-size: 2em;
    }
    span::after{
        background: none repeat scroll 0 0 transparent;
     
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
    }
   
@media  (max-width:991px) {
    .customers #h3{
            font-size: 17px;
            position: relative;
            left: -100px;
            display: flex;
    }
    .about{
        position: relative;
        top: 200px;
        display: flex;
        flex-direction: column;
        width: 100%;
        padding: 20px;
    }
    #about{
        text-align: center;
        height: 130vh;
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
</style>