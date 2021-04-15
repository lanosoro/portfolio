<template>
  <section id="contactus">
      <div class="hero" data-aos="slide-up" data-aos-duration="1500">
          <div data-aos="slide-down" data-aos-duration="1500" class="contactinfo">
              <div class="info" data-aos="ease-in-back" data-aos-delay="50" data-aos-duration="2000">
                  <h2>
                      Contact info
                  </h2>
                   <ul class="localeinfo">
          <li>
            <span style="font-size:13px"
              ><i></i>MEDILAB AND ALLIED PRODUCTS (K) LTD,</span
            >
          </li>
          <li>
            <span
              ><i class="fa fa-map-marker" aria-hidden="true"></i> GENERAL
              WARUINGE ROAD, OLD RACE COURSE, STAREHE COURT 7638 (2), P.O BOX
              14705-00400, NAIROBI, KENYA</span
            >
          </li>
          <li>
            <span
              ><i class="fa fa-phone"></i> +254 721 811 499, +254 734 768 110,
              +254 020 4401525, +254 774 768 110</span
            >
          </li>
          <li>
            <span style="line-height:1.5em; "
              ><i class="fa fa-envelope"></i> sales@medilaballied.com
              info@medilaballied.com medilab.alliedproductsltd@gmail.com</span
            >
          </li>
        </ul>
         <ul class="sci">
          <li>
            <a href="#"><i class="fab fa-facebook-f"></i></a>
          </li>
          <li>
            <a href="#"><i class="fab fa-twitter"></i></a>
          </li>
          <li>
            <a href="#"><i class="fab fa-instagram"></i></a>
          </li>
          <li>
            <a href="#"><i class="fab fa-linkedin-in"></i></a>
          </li>
        </ul>
              </div>
          </div>
          <div class="contactform">
              <h2>send us a message</h2>
              <div class="formbox">
                  <div class="inputbox w50">
                      <input type="text" required>
                      <span>firstname</span>
                  </div>
                  <div class="inputbox w50">
                      <input type="text" required>
                      <span>lastname</span></div>
                  <div class="inputbox w50">
                      <input type="email" required>
                      <span>Email</span>
                      </div>
                  <div class="inputbox w50">
                      <input type="tel" required>
                      <span>Phone number</span>
                      </div>
                  <div class="inputbox w100">
                      <textarea id="textarea" required></textarea>
                      <span>write your message here...</span>
                      </div>
                    <div class="inputbox w100">
                      <a type="submit" value="Send" id="send" href="mailto:medilab.alliedproductsltd@gmail.com">send</a>
                      
                      </div>
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
.info{
    text-align: left;
}
.info h2{
    padding-left:50px ;
    font-weight: 700;
    font-size: 35px;
    color: #fff;

}
.localeinfo{
    list-style: none;
    text-align: left;
    line-height: 1.7rem;
    
}
.localeinfo li{
    margin-bottom: 20px;
    color: white;
    
}
.hero{

  position: relative;
  width: 600px;
  min-height: 550px;
  display: flex;
  z-index: 1000;
  

    
}
.hero .contactinfo{
    position: relative;
   top: 0px;
left: 0px;
top: 50px;

width: 350px;
height: 450px;
    background: #90c4f9;
    z-index:1 ;
    display: flex;
    justify-content: center;
    flex-direction: column;
    justify-content: space-between;
    box-shadow: 0 20px 25px rgba(0, 0, 0, 0.145);
}
.hero .contactform{
    position: absolute;
    padding: 70px 50px;
    padding-left:250px ;
    margin-left: 150px;
    width:700px;
    height: 100%;
    background: #fff;
    box-shadow: 10px 50px 50px rgba(0, 0, 0, 0.145);


}
.hero .contactform h2{
    font-size: 24px;
    font-weight: 550;
    color: black;
}
.hero .contactform .formbox{
    position: relative;
    display: flex;
    justify-content: space-between;
    flex-wrap: wrap;
    padding-top:30px;
}
.hero .contactform .formbox .inputbox{
    position: relative;
    margin-bottom:35px;

}
.hero .contactform .formbox .inputbox.w50{
    width: 47%;
}
.hero .contactform .formbox .inputbox.w100{
    width: 100%;
}
.hero .contactform .formbox .inputbox input,
.hero .contactform .formbox .inputbox textarea{
    width: 100%;
    resize: none;
    padding: 5px 0;
    font-size: 18px;
    font-weight: 300;
    color: #333;
    border: none;
    outline: none;
    border-bottom: 1px solid #777;
}
.hero .contactform .formbox .inputbox textarea{
    height: 120px;
}
.hero .contactform .formbox .inputbox span{
    position: absolute;
    left: 0;
    padding: 5px 0;
    pointer-events: none;
    font-size: 18px;
    font-weight: 300;
    transition: 0.3s;

}
 input:focus ~ span,
 input:valid ~ span,
 textarea:focus ~ span,
 textarea:valid ~ span{
    transform: translateY(-20px);
    font-size: 12px;
    font-weight: 400;
}
#send
{
    position: relative;
    cursor: pointer;
    z-index: 100000;
    background: #90c4f9;
    color: #fff;
    border: none;
    max-width: 150px;
    padding: 12px;
    border-radius:15px;
}
#send:hover{
    background: #60c3f0;
}
section{
    height: 100vh;
    display: flex;
    align-items: center;
    justify-content: center;
    background: white;

}
section::before{
    content: '';
    position: absolute;
  
    left: 0;
    width: 50%;
    height: 100vh;
    background: #90c4f9;

}
/* responsive */
@media(max-width:1200px)
    {
        .hero{
            width: 90%;
            min-width: auto;
            margin: 20px;
        }
        .hero .contactinfo{
            top: 0;
            height: 550px;
            position: relative;
            box-shadow: none;
            

        }
        .hero .contactform{
               position: relative;
                width: 70vw;
                padding-left: 0px;
                margin-left: 0;
                padding: 40px;
                height: 550px;
        }
    }
    @media(max-width:991px){
        section{
            background: #90c4f9;
        }
        section::before{
            display: none;
        }
        .hero{
            margin: 30px;
            padding: 20px;
            display: flex;
            flex-direction: column-reverse;
        }
          .hero .contactinfo{
            top: 0;
            height: auto;
            position: relative;
            box-shadow: none;
            width: 70vw;
           font-size: 12px;
            margin-bottom: 70px;
            box-shadow: 0 30px 30px rgb(0 0 0 / 30%);}
    
            .hero .contactform{
                height: auto;
                widows: 100%;
                display: flex;
                flex-direction: column;
            }
            .sci li {
                list-style: none;
                margin-left: -36px;
                margin-right: 13px;
                padding: 5px;
                position: relative;
                left: 30px;
}}
@media (max-width:440px){
                section{
                    height: 200vh;
                }
               .sci li {
                list-style: none;
                margin-left: -36px;
                margin-right: 13px;
                padding: 5px;
                position: relative;
                left: 10px;
}
  .hero .contactform{
                height: auto;
               width: 80vw;
               border-radius: 8px;
                display: flex;
                flex-direction: column;
            }
    .hero .contactinfo{
        width: 80vw;
        top: 40px;
        border-radius:8px ;
        padding: 20px;
    }
}
</style>
