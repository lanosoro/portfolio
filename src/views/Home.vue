/* eslint-disable vue/no-unused-vars */
/* eslint-disable @typescript-eslint/no-this-alias */
<template>
<v-layout class="main" style="font-family: 'Comfortaa', cursive; font-size:16px">
  <Nav/>
    <div class="home col-lg-12 col-md-12 col-sm-12  ">
       <div class="hero col-lg-4 col-md-12 col-sm-12">
      <span class="heading" >
       <transition name="fade">
          <h1 style="display:block; color:white; font-weight:700; font-size:49px; text-align:left; margin-top:30px">
          welcome! <br>
          medilab & allied limited
        </h1>
       </transition>
        <p data-aos="slide-right" data-aos-duration="500" style="font: size 1.1em;">Medilab & Allied 
          Products K Ltd is 
          located in Nairobi, 
          Kenya, a Chemical & 
          Research/Medical 
          Distributor</p>
        <p data-aos="slide-left" data-aos-duration="1500">
          We want to be a 
          leading provider of 
          products and 
          services to the 
          Medical, Water 
          Treatment and 
          scientific Sectors.</p>
         <scrollto data-aos="slide-up" data-aos-duration="1900"
                                        href="#products"
                                        class="nav-link"
                                    >Our products
                                    </scrollto>
      </span>
          <!-- <div class="card-1">
        <img src="..\assets\Medical_supplies_small.jpg" alt="" class="image">
      </div> -->
     
    </div>

    <div class="hero_img" >
        <img data-aos="fade-up" data-aos-duration="1900" src="../assets/doc.png" alt="" class="about_img" >
        
    </div>

  </div>

  <products/>
  <about/>
  <contacus/>
  <Footer/>
</v-layout>

</template>

<script>
import products from '@/components/products.vue'
import About from '@/components/about.vue'
import Footer from '@/components/footer.vue'
import Contacus from '@/components/contacus.vue'
import Nav from '@/components/nav.vue'
import scrollto from '@/components/scrollto';


export default {
  components: { products, About, Footer, Contacus,Nav,scrollto},
   
}

    
</script>

<style scoped>
body{
background-color:#2C3E50;
}
#slider{
width:100%;
}
#hero{
  padding: 30px;
  width:500px ;
  height: 100%;
  position: relative;
  right: 0;
}

.home{
  height: 100vh;
  width: 100vw;
  background: #90c4f9;
  z-index: 1000;
  display: flex;
  gap: 10vw;
  flex-direction: row;
  padding: 0 150px;
}
.card-1{
  height: 500px;
  border-radius: 15px;
  background: white;
  width: 300px;
}
img{
  height: 80vh;
  /* width: 100vw; */
  position: relative;
  top: 0px;
  width: 600px;
}
.main{
  display: flex;
  flex-direction: column;

}
.hero{
  height: 80vh;
  width: 100%;
  font-size: 300px;

  display: flex;
  flex-direction: row;
  padding: 30px;
}
.nav-link{
  font-size: 20px;
  background: white;
  padding: 10px 15px;
  color: #90c4f9;
  cursor: pointer;
  border-radius: 20px;
  box-shadow: 0 3px 3px rgba(0, 0, 0, 0.268);
}
p{
  font-size: 20px;
  text-align: left;
  flex-wrap:wrap ;
  display: flex;
}
/* .heading{
  width: 60vw;
  background: rgba(0, 0, 0, 0.207);
  height: 67vh;
  padding: 10px 30px;
  position: relative;
  border-radius:10px ;
  box-shadow: 0px 10px 10px rgba(255, 255, 255, 0.481);
} */
@media (max-width:500px){
  #hero{
    display: none;
  }
  .main{
    width:100% ;
  }
  .hero_img{
    display: none;
  }
  .home {
    height:100vh;
 
  }
  h1{
    font-size: 34px !important;
  }
  #p{
    font-size: 14px;
  }
  .nav-link{
    width: 50%;
    font-size:14px;
  }
  .hero{
    justify-content: center;
    align-content: center;
  }
}

</style>