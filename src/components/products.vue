<template>
<section id="products">
      <div class="products col-lg-12 col-sm-12 col-md-12">
      <div class="hero">
          <!-- <img src="../assets/tech.jpg" alt=""> -->
          <h2>Our product range</h2>
             <ul data-aos="slide-up" data-aos-duration="1550">
                 <li data-aos="slide-up" data-aos-duration="1150" class="productitems">1</li>
                 <li data-aos="slide-up" data-aos-duration="1350" class="productitems">w</li>
                 <li data-aos="slide-up" data-aos-duration="1450" class="productitems">4</li>
                 <li data-aos="slide-up" data-aos-duration="1550" class="productitems">5</li>
                 <li data-aos="slide-up" data-aos-duration="1650" class="productitems">7</li>
                 <li data-aos="slide-up" data-aos-duration="1750" class="productitems">8</li>
                 <li data-aos="slide-up" data-aos-duration="1850" class="productitems">9</li>
                 <li data-aos="slide-up" data-aos-duration="1950" data-aos-delay="60" class="productitems">0</li>
             </ul>
          </div>
      </div>

</section>
</template>

<script>
export default {

}
</script>

<style scoped>
ul{
    display: flex;
    flex-flow: row wrap;
    justify-content: space-evenly;
    padding: 0;
    margin: 0;
    list-style: none;
}
ul .productitems{
    background: #1080f03f;
    box-shadow:0 5px 5px rgba(0, 0, 0, 0.254);
    padding: 5px;
    width: 300px;
    position: relative;
    top:30px ;
justify-content: space-evenly;
    height: 250px;
    margin-top: 10px;
    line-height: 150px;
    border-radius:10px ;
    color: white;
    font-weight:bold

}
    .products{
        height: 40vh;
        width: 100%;
        
    }
    section{
        height:100vh;
        display: flex;
        flex-flow: row wrap;

         }
    .hero{
        display: flex;
        width: 100%;
        flex-direction: column;
        margin-top: 30px;

    position: relative;
    left: -20px;
    }
    .a{
        padding: 30px;
        width: 300px;
        height: 300px;
        
        background: rgba(192, 248, 255, 0.07);
        border-radius:30px ;
        box-shadow: 3px 3px 3px rgba(0, 0, 0, 0.09);
        margin-right: 30px;
        z-index: 100000;
    }
    @media(max-width:991px){
        .hero{
            width: 100vw;
            display: flex;
            flex-direction: column;
            justify-content: center;
        }
        section{
            justify-content: center;
            height: 200vh;
        }

    }
    @media (max-width:500px) {
        section{
            height: 255vh;
        }
    }
</style>