<template>
<section id="products">
      <div class="products col-lg-12 col-sm-12 col-md-12">
      <div class="hero">
          <!-- <img src="../assets/tech.jpg" alt=""> -->
          <h2>Our product range</h2>
             <ul data-aos="fade-up" data-aos-duration="1550">
                 <li data-aos="fade-up" data-aos-duration="1150"  class="productitemss"><img src="../assets/Medical_supplies_small.jpg" alt="" height="100%" width="100%" style="border-radius:10px;"></li>
                 <li data-aos="fade-up" data-aos-duration="1350"  class="productitems"><img src="../assets/londro.jpg" alt="" height="100%" width="100%" style="border-radius:10px;"></li>
                 <li data-aos="fade-up" data-aos-duration="1450"  class="productitems"><div class="overlay"><img src="../assets/cleaner.jpg" alt="" height="100%" width="100%" style="border-radius:10px;">
                    </div></li>
                 <li data-aos="fade-up" data-aos-duration="1550"  class="productitems"><img src="../assets/water.jpg" alt="" height="100%" width="100%" style="border-radius:10px;"></li>
                 <li data-aos="fade-up" data-aos-duration="1650"  class="productitems"><img src="../assets/chemlab.jpg" alt="" height="100%" width="100%" style="border-radius:10px;"></li>
                 <li data-aos="fade-up" data-aos-duration="1750"  class="productitems"><img src="../assets/Medical_supplies_small.jpg" alt="" height="100%" width="100%" style="border-radius:10px;"></li>
                 <li data-aos="fade-up" data-aos-duration="1850"  class="productitems"><img src="../assets/Medical_supplies_small.jpg" alt="" height="100%" width="100%" style="border-radius:10px;"></li>
                 <li data-aos="fade-up" data-aos-duration="1950"  data-aos-delay="60" class="productitems"><img src="../assets/Medical_supplies_small.jpg" alt="" height="100%" width="100%" style="border-radius:10px;"></li>
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
    gap: 20px;
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
ul .productitemss{
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
.overlay{
    width: 100%;
    height: 100%;
    background: rgba(0, 0, 0, 0);
    opacity: 0.5;
  
    transition: all 2s ease-out;
    position: relative;
    z-index: 1;
}
.overlay:hover{
    opacity: 1;

}

.ul .productitemss::after,
.ul .productitemss::before {
	position: absolute;
	z-index: 1;
	width: 100%;
	height: 50%;
	transition: transform .4s ease-out;
	color: #fff;
}
.ul .productitemss::after {
	content: attr(data-title);
	top: 0;
	padding-top: 55px;
	transform: translateY(-100%) scale(.8);
	background: rgba(0,0,0,.4);
	font-size: 3.5rem;
	font-weight: 300;
	font-family: Merriweather, serif;
	text-align: center;
}
.ul .productitemss::before {
	content: attr(data-description) "…";
	top: 50%;
	padding: 20px;
	transform: translateY(100%) scale(.8);
	background: rgba(107,38,68,.6);
	-webkit-backdrop-filter: blur(10px);
	backdrop-filter: blur(10px);
	color: #f1f1f1;
	font-size: 1.5rem;
}
.ul .productitemss:hover::after,
.ul .productitemss:hover::before {
	transform: translateY(0%) scale(1);
}
.products{
        height: 40vh;
        width: 100%;
        
    }
section{
        height:130vh;
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
            height:140vh;
        }
        ul .productitems{
        background: #1080f03f;
        box-shadow:0 5px 5px rgba(0, 0, 0, 0.254);
        padding: 5px;
        width: 150px;
        position: relative;
        top:30px ;
        justify-content: space-evenly;
        height: 120px;
        margin-top: 10px;
        line-height: 150px;
        border-radius:10px ;
        color: white;
        font-weight:bold

}
    }
</style>