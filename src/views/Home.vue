<template>
<v-layout class="main">
  <Nav/>
    <div class="home col-lg-12 col-md-12 col-sm-12  ">
    <div class="hero col-lg-4 col-md-12 col-sm-12">
      <span class="heading" >
        <p data-aos="fade-in-up" style="display:block; color:white; font-weight:700; font-size:49px; text-align:left; margin-top:30px">
          welcome! <br>
          medilab & allied limited
        </p>
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
      <!-- <img src="../assets/mash.jpg" alt="" class="about_img" height="400px"> -->
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
  components: { products, About, Footer, Contacus,Nav,scrollto }

}
    
</script>

<style scoped>
.home{
  height: 100vh;
  width: 100vw;
  background: #90c4f9;
  z-index: 1000;
}
.card-1{
  height: 500px;
  border-radius: 15px;
  background: white;
  width: 300px;
}
img{
  height: 30vh;
  position: relative;
  top: 0px;
  width: 300px;
}

.hero{
  height: 100vh;
  width: 100%;
  font-size: 300px;
  display: flex;
  flex-direction: row;
  padding: 20px;
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
}
@media (max-width:500px){
  .main{
    width:100% ;
  }
}

</style>