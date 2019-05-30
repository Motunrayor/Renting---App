<template>
  <div class="testimonial">
        <h2>Testimonials from Clients</h2>

    <span>
      <div>
            <div id="image1"></div>
        <div  id="body">
            <p>The service was 1005 excellent and I<br> love the property. It is rare seeing people<br> so hoest about what they have to offer</p>
            <div id="a">
            <h3 >Reogna Zeus</h3>
            <h4 >Founder, The Reach</h4>
            </div>
        </div>
     </div>
     </span>

    <span>
      <div>
            <div id= "image2"></div>
        <div  id="body2">
            <p id="b">The service was 1005 excellent and I<br> love the property. It is rare seeing people<br> so hoest about what they have to offer</p>
        <div id="c">
            <h3 >Reogna Zeus</h3>
            <h4 >Founder, The Reach</h4>
        </div>
        </div>
      </div>
    </span>

    <span>
      <div>
            <div id= "image3"></div>
        <div  id="body3">
            <p id="d">The service was 1005 excellent and I<br> love the property. It is rare seeing people<br> so hoest about what they have to offer</p>
        <div id="e">
            <h3 >Reogna Zeus</h3>
            <h4 >Founder, The Reach</h4>
        </div>
        </div>
      </div>
    </span>
       
 </div>
</div>
</template>

<script>
export default {
  name: 'testimonial',
  
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
.testimonial{
  position: relative;
    width: 100vw;
    height:110vh;
    background:#ffffff;
    top:177px;
    left:1px;
}
#image1{
  position: absolute;
  width: 308px;
  height: 180px;
  margin-left: 234px;
  margin-top: 172px;
  background: url("../assets/testimonial.jpg");
}
  #image2{
  position: absolute;
  width: 308px;
  height: 180px;
  margin-left: 593px;
  margin-top: 174px;
  background: url("../assets/testimonial.jpg");
}
#image3{
  position: absolute;
  width: 308px;
  height: 180px;
  margin-left: 952px;
  margin-top: 176px;
  background: url("../assets/testimonial.jpg");
}

h2{
  position: relative;
  width: 288px;
  height: 32px;
  left: 576px;
  top: 100px;
  text-align:center;
  font-family: Roboto;
  font-style: normal;
  font-weight: bold;
  font-size: 24px;
  line-height: 28px;
  color: #0000dd;
}
p{
  position: absolute;
  width: 256px;
  height: 112px;
  margin-left: 257px;
  margin-top: 402px;
  font-family: Roboto;
  font-style: normal;
  font-weight: normal;
  font-size: 14px;
  line-height: 16px;
  text-align: center;
  color: #000;
}
#a{
  position: absolute;
  width: 176px;
  height: 40px;
  margin-left: 294px;
  margin-top: 450px;
  font-family: Roboto;
  font-style: normal;
  font-weight: bold;
  font-size: 14px;
  line-height: 16px;
  text-align: center;
  color: #000000;
}
#b{
  position: absolute;
  width: 256px;
  height: 112px;
  left: 364px;
  margin-top: 402px;
  font-family: Roboto;
  font-style: normal;
  font-weight: normal;
  font-size: 14px;
  line-height: 16px;
  text-align: center;
  color: #000;
}
#c{
  position: absolute;
  width: 176px;
  height: 40px;
  left: 653px;
  margin-top: 450px;
  font-family: Roboto;
  font-style: normal;
  font-weight: bold;
  font-size: 14px;
  line-height: 16px;
  text-align: center;
  color: #000000;
}
#d{
  position: absolute;
  width: 256px;
  height: 112px;
  left: 712px;
  margin-top: 402px;
  font-family: Roboto;
  font-style: normal;
  font-weight: normal;
  font-size: 14px;
  line-height: 16px;
  text-align: center;
  color: #000;
}
#e{
  position: absolute;
  width: 176px;
  height: 40px;
  left: 1000px;
 margin-top: 450px;
  font-family: Roboto;
  font-style: normal;
  font-weight: bold;
  font-size: 14px;
  line-height: 16px;
  text-align: center;
  color: #000000;
}
@media screen and (max-width: 768px){
  .testimonial{
  position: relative;
    width: 100vw;
    height:230vh;
    background:#ffffff;
    top:172px;
    left:2px;
  }
  h2{
  position: absolute;
  width: 288px;
  height: 32px;
  left: 200px;
  top: 70px;
  color: #0000dd;
}
#image1{
  position: absolute;
  width: 308px;
  height: 180px;
  margin-left: 234px;
  margin-top: 172px;
  background: url("../assets/testimonial.jpg");
}
p{
  position: absolute;
  width: 256px;
  height: 112px;
  margin-left: 257px;
  margin-top: 402px;
  text-align: center;
  color: #000;
}
#a{
  position: absolute;
  width: 176px;
  height: 40px;
  margin-left: 294px;
  margin-top: 450px;
  text-align: center;
  color: #000000;
}
#image2{
  position: absolute;
  width: 308px;
  height: 180px;
  margin-left: 234px;
  margin-top: 572px;
  background: url("../assets/testimonial.jpg");
}
#b{
  position: absolute;
  width: 256px;
  height: 112px;
  left: 0px;
  margin-top: 802px;
  text-align: center;
  color: #000;
}
#c{
  position: absolute;
  width: 176px;
  height: 40px;
  left: 290px;
  margin-top: 850px;
  text-align: center;
  color: #000000;
}
#image3{
  position: absolute;
  width: 308px;
  height: 180px;
  margin-left: 234px;
  margin-top: 972px;
  background: url("../assets/testimonial.jpg");
}
#d{
  position: absolute;
  width: 256px;
  height: 112px;
  left: 0px;
  margin-top: 1202px;
  text-align: center;
  color: #000;
}
#e{
  position: absolute;
  width: 176px;
  height: 40px;
  left: 290px;
  margin-top: 1250px;
  text-align: center;
  color: #000000;
}
@media screen and (max-width: 768px){
  
}
}
</style>