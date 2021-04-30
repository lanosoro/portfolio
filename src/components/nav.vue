/* eslint-disable @typescript-eslint/no-unused-vars */
<template>
<div class="main">
   <section class="top-contact">
     <ul class="sci" style="position:relative; ">
          <li>
            <a href="#"><i class="fab fa-facebook-f"></i></a>
          </li>
          <li>
            <a href="#"><i class="fab fa-twitter"></i></a>
          </li>
         
          <li>
            <a href="mailto:sales@medilaballied.com"><i class="fa fa-envelope"></i> </a>
          </li>
          <li><a href="tel:+254 721 811 499"><i class="fa fa-phone"></i></a></li>
        </ul>
        <div class="temail">
          <br>
          <br>
          
        </div>

   </section>
<section>
   
    <img src="../assets/logo-medilab-removebg-preview.png" alt="" class="logo">
        <div id="nav" class="col-md-8 col-sm-8 col-lg-8">
         <scrollto href=".main" class="nav-link">Home</scrollto>
         <scrollto href="#products" class="nav-link">products</scrollto>
         <scrollto href="#about" class="nav-link">About</scrollto>
         <scrollto href="#contactus" class="nav-link">Contact us</scrollto>
                  
    </div>
      <div class="humburger" @click="myFunction(this)">
      <div class="bar1"></div>
      <div class="bar2"></div>
      <div class="bar3"></div>
    </div>  
</section>
</div>
</template>
<script>

import scrollto from '@/components/scrollto';

export default {
   components: {
            scrollto,
      
        },
    method:{}
}
</script>
<style lang="stylus" scoped>
.temail
    display flex
    flex-wrap wrap
    flex-direction row
    position relative
    text-align left
    left: 70vw
.temail a   
    text-decoration none
    color grey
  
.top-contact
  background white
  width 100vw
  height 100px
  align-items center

section
  display flex
  flex-direction row
  background white
  height 100px
  width 100vw
.humburger
  display block
#nav
  flex-wrap wrap
  display flex
  flex-direction row
  justify-content flex-end
  background white
.nav-link
  color: black;
  text-transform: uppercase;
  text-decoration: none;
  letter-spacing: 0.15em;
  font-weight 700
  font-size 11px
  display: inline-block;
  padding: 19px 50px;
  position: relative;
  margin 0px 20px
.logo
  margin-right 20vw
  margin-top 10px
  height 100px

 
.nav-link:after
  background: none repeat scroll 0 0 transparent;
  bottom: 39px;
  content: "";
  display: block;
  height: 2px;
  left: 50%;
  position: absolute;
  background: black;
  transition: width 0.3s ease 0s, left 0.3s ease 0s;
  width: 0;

.nav-link:hover:after 
  width: 100%; 
  left: 0; 

@media (max-width 1030px)
  .top-contact
      background white
      width 100vw
      height 52px
      align-items center
  .humburger
  
    width 20%

  section
    display flex
    flex-direction column
    background white
    height 125px
    width 100vw
  #nav
    flex-wrap wrap
    display flex
    flex-direction row
    justify-content space-evenly
    background white
  .nav-link
    color: black;
    text-transform: uppercase;
    text-decoration: none;
    letter-spacing: 0.15em;
    font-weight 700
    font-size 9px
    display: inline-block;
    padding: 5.5px 5px;
    position: relative;
    margin 0px
  .nav-link:after
    background: none repeat scroll 0 0 transparent;
    bottom: 39px;
    content: "";
    display: none;
    height: 2px;
    left: 50%;
    position: absolute;
    background: black;
    transition: width 0.3s ease 0s, left 0.3s ease 0s;
    width: 0;

.nav-link:hover:after 
  width: 100%; 
  left: 0; 
.logo
  height 50px
  width 100px
.change .bar1 {
  -webkit-transform: rotate(-45deg) translate(-9px, 6px);
  transform: rotate(-45deg) translate(-9px, 6px);
}

.change .bar2 {opacity: 0;}

.change .bar3 {
  -webkit-transform: rotate(45deg) translate(-8px, -8px);
  transform: rotate(45deg) translate(-8px, -8px);
}

 
 
  
</style>