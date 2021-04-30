<template>
  <footer>
    <div class="container">
      <div class="sec aboutus">
        <h3>
          About Us
        </h3>
        <p>
          Medilab & Allied Products K Ltd is a Kenyan company, which is
          committed to providing Medical and Research Reagents and Consumables,
          Water treatment chemicals, Cooling Tower/Boiler/Chiller chemicals and
          Condition Monitoring reagents/Sensors.
        </p>
        
      </div>
      <div class="sec links">
        <h3>
          Other Links
        </h3>
        <ul>
          <li><a href="#">About Us</a></li>
          <li><a href="#">Contact Us</a></li>
          <li><a href="#">Services</a></li>
          <li><a href="#">Careers</a></li>
          <li><a href="#">Terms & conditions</a></li>
        </ul>
      </div>
      <div class="sec contact">
           <h3>Contact Info</h3>
        <ul class="info">
        
          <li>
            <span style="font-size:13px"
              ><i></i>MEDILAB AND ALLIED PRODUCTS (K) LTD,</span
            >
          </li>
          <li>
            <span
              > <a href="https://www.google.com/maps/place/Starehe+Court/@-1.2768852,36.8352839,17z/data=!3m1!4b1!4m5!3m4!1s0x182f16cdbc9fd05f:0xaa79ee45ae361e9!8m2!3d-1.2768852!4d36.8374726"><i class="fa fa-map-marker" aria-hidden="true"></i> GENERAL
              WARUINGE ROAD, OLD RACE COURSE, STAREHE COURT 7638 (2), P.O BOX
              14705-00400, NAIROBI, KENYA</a></span
            >
          </li>
          <li>
            <span
              ><i class="fa fa-phone"></i> +254 721 811 499, ,
              +254 020 4401525, +254 774 768 110</span
            >
          </li>
          <li>
            <span style="line-height:1.5em;"
              > <a href="mailto:sales@medilaballied.com"><i class="fa fa-envelope"></i> sales@medilaballied.com</a>
              <a href="mailto:info@medilaballied.com">info@medilaballied.com</a> <a href="mailto:medilab.alliedproductsltd@gmail.com">medilab.alliedproductsltd@gmail.com</a></span
            >
          </li>
        </ul>
      </div>
    </div>
    <div id="bottomfooter">
      <p style="font-size:12px;">
        Copyright © {{ new Date().getFullYear() }}· All Rights Reserved ·
        Medilabs Ltd Web design by ·<span id="link">
          <a href="http://fineteklabs.com"> Fineteklabs</a>
        </span>
      </p>
      
    </div>
  </footer>
</template>

<script>
export default {};
</script>

<style>
.info span a{
  text-decoration: none;
  color: white;
  margin: 5px;
  flex-wrap: wrap;
  display: block;
}
.info span a:hover{
  text-decoration: underline;
  color: black;
}
footer {
  display: flex;
  justify-content: space-between;
 
  min-height: 50vh;
  flex-direction:row;
  background: #0074a5;
  
  width: 100%;
  height: auto;
  position: relative;
  flex-wrap: wrap;
}
footer .container {
  display: flex;
  justify-content: space-between;
  flex-wrap: wrap;
  margin: 20px 20px;
  flex-direction: row;
  max-width: 100%;
  top: -18px;
  left: -18px;
  position: relative;
}
footer .container .sec {
 
  font-size: 14px;
}
footer .container .sec.aboutus {
  width: 40%;
  color: white;
  word-spacing: 0.2em;
  text-align: left;
  flex-wrap: wrap;
}
.sci {
  margin-top: 20px;
  display: flex;
 
}
.sci li {
  list-style: none;
   position: relative;
  left: 20px;
}
.sec.aboutus h3::before {
  content: "";
  position: absolute;

  background: white;
  height: 2px;
  margin-top: 40px;
  box-sizing: border-box;
  width: 100px;
}
.sci li a {
  display: inline-block;
  width: 40px;

  height: 40px;
  background-color: rgba(255, 255, 255, 0.2);
  display: flex;
  justify-content: center;
  align-items: center;
  border-radius: 50%;
  color: grey;
  text-decoration: none;
  margin-right: 15px;
  transition: all 1s ease;
}
.sci li a:hover {
  background: white;
  color: #0074a5;
  box-shadow:0px 10px 6px rgba(0, 0, 0, 0.261);
}
.links li a {
  display: inline-block;
  display: flex;
  justify-content: center;
  align-items: center;

  color: white;
  text-decoration: none;
  margin-right: 35px;
  transition: all 1s ease;
}
.links li {
  list-style: none;
}
footer .container .links {
  width: 25%;
  position: relative;
  color: white;
}
.links ul li {
  text-decoration: none;
  margin-top: 10px;
  margin-bottom: 10px;
  justify-content: flex-start;
  display: flex;
  text-align: left;
  align-self: auto;
  align-items: left;
  flex-wrap: wrap;
  transition: all 0.1s ease-in;
  word-spacing: 0.2em;
}
.links ul li:hover {
  font-weight: 600;
  font-size: 19px;
}
.links h3{
  text-align: left;
}
.links h3::before {
  content: "";
  position: absolute;
  background: white;
  height: 2px;
  margin-top: 40px;
  box-sizing: border-box;
  width: 100px;
}
.contact {
  width: calc(35% - 70px);
  margin-right: 0 !important;
  color: white;
  list-style: none;
}
.contact .info {
    position: relative;
    width: 300px;
    left: 0px;
}
.contact .info li {
  display: flex;
  text-align: left;
  flex-wrap: wrap;
  margin-bottom: 16px;
  word-spacing: 0.1em;
  padding-top: 6px;
}
.contact h3{
  text-align: left;
}
.contact h3::before {
  content: "";
  position: absolute;
  background: white;
  height: 2px;
  margin-top: 40px;
  box-sizing: border-box;
  width: 100px;
}
#bottomfooter {
  position: absolute;
  left: 0;
  right: 0;
  font-size: 12px;
  
  bottom: 0px;
  background: #90c4f9;
  flex-direction: column;
  flex-wrap: wrap;
  width: 100%;
  padding: 30px;
  color: white;
  justify-content: center;
  text-align: center;
    font-size: 13px;
    justify-content: flex-end;
    align-content: center;
    align-items: center;
    position: relative;
   
    flex-wrap: wrap;
}
.sec{
  left: 0px;
}
@media screen and (max-width: 991px) {
  footer {
    padding: 20px;
  }
  footer .container {
    flex-direction: column;
    justify-content: center;
    position: relative;
    left: -10px;
  }
  .links ul{
    text-align: left;
    position: relative;
    left: 0px;
    width: 300px;
  }
  .container .sec {
    margin-right: 0;
    margin-bottom: 40px;
  }
  #bottomfooter {
    position: absolute;
    left: auto;
    right: 0;
    bottom: 0px;
    background: #28b6e7;
    width: 100vw;
    padding: 8px 40px;
    color: white;
    font-weight: 400;
    font-size: 18px;
    justify-content: center;
    text-align: center;
    margin-top: 20px;
  }
  h3 {
    margin-bottom: 0.5rem;
    font-family: inherit;
    font-weight: 500;
    line-height: 1.2;
    width: 300px;
    color: inherit;
  }
  .contact .info {
    position: relative;
    width: 80vw;
    flex-wrap: wrap;
  }
}
@media screen and (max-width: 600px) {
  footer .container .sec.aboutus p {
    width: 300px;
  }
  footer .container .sec.aboutus{
    text-align: left;
    justify-items: center;
    left: 0px;
    position: relative;
  }
    #bottomfooter {
    position: absolute;
    left: auto;
    right: 0;
    bottom: 0px;
    background: #28b6e7;
    width: 100vw;
    padding: 8px 40px;
    color: white;
    font-weight: 400;
    font-size: 18px;
    justify-content: center;
    text-align: center;
    margin-top: 20px;
  }
}
</style>
