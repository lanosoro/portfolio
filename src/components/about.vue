<template>
  <section id="about">
      <div class="about col-lg-12 col-sm-12 col-md-12">
                    
           <div class="about-text" data-aos="fade-in" data-aos-duration="2000">
               <h2>About us</h2>
               <p>
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
</template>

<script>
export default {

}
</script>

<style scoped>
    .about{
        height: 40vh;
        width: 50%;
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
    
    }
    .about-text p{
        font-size: 1.5em;
        font-weight: 500;
        line-height: 2rem;
    }
    section{
        height: 100vh;
    }
@media  (max-width:991px) {
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
}
</style>