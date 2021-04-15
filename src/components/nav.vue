<template>
<section>
    <img src="../assets/logo-medilab-removebg-preview.png" alt="" class="logo">
        <div id="nav" class="col-md-8 col-sm-8 col-lg-8">
         <scrollto
                                        href="#about"
                                        class="nav-link"
                                    >Home
                                    </scrollto>
                                      <scrollto
                                        href="#products"
                                        class="nav-link"
                                    >products
                                    </scrollto>
                                    <scrollto
                                        href="#about"
                                        class="nav-link"
                                    >About
                                    </scrollto>
                                    <scrollto
                                        href="#contactus"
                                        class="nav-link"
                                    >Contact us
                                    </scrollto>
                                  
    </div>
</section>
</template>
<script>
import scrollto from '@/components/scrollto';

export default {
   components: {
            scrollto,
      
        }
}
</script>
<style lang="stylus" scoped>
section
  display flex
  flex-direction row
  background #90c4f9
#nav
  flex-wrap wrap
  display flex
  flex-direction row
  justify-content flex-end
  background #90c4f9
.nav-link
  color: white;
  text-transform: uppercase;
  text-decoration: none;
  letter-spacing: 0.15em;
  font-weight 700
  display: inline-block;
  padding: 19px 50px;
  position: relative;
  margin 0px 20px
.logo
  margin-right 20vw
  margin-top 20px
.nav-link:after
  background: none repeat scroll 0 0 transparent;
  bottom: 29px;
  content: "";
  display: block;
  height: 2px;
  left: 50%;
  position: absolute;
  background: #fff;
  transition: width 0.3s ease 0s, left 0.3s ease 0s;
  width: 0;

.nav-link:hover:after 
  width: 100%; 
  left: 0; 

@media (max-width 900px)
  .nav-link
    display none
media (min-width: 576px)
  .col-sm-8
      -ms-flex: 0 0 66.666667%;
      flex: 0 0 66.666667%;
      max-width: 10%;

</style>