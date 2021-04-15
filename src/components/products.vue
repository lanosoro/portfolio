<template>
<section id="products">
      <div class="products col-lg-12 col-sm-12 col-md-12">
      <div class="hero">
          <!-- <img src="../assets/tech.jpg" alt=""> -->
          
              <div class="a" data-aos="slide-up" data-aos-duration="1400" >
                  Lorem ipsum dolor sit amet, consectetur adipisicing elit. Natus, ipsam!
              </div>
              <div class="a" data-aos="slide-up" data-aos-duration="1600">
                  Lorem ipsum dolor sit amet consectetur adipisicing elit. Tempore, maxime?
              </div>
              <div class="a"  data-aos="slide-up" data-aos-duration="1800">
                  Lorem ipsum dolor sit amet consectetur adipisicing elit. Beatae, ab.
              </div>
          </div>
      </div>

</section>
</template>

<script>
export default {

}
</script>

<style scoped>
    .products{
        height: 40vh;
        width: 100%;
        
    }
    section{
        height:100vh;
    }
    .hero{
        display: flex;
        width: 100%;
        flex-direction: row;
        margin-top: 30px;
        justify-content: center;
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
        }
    }
</style>