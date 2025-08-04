<template>
    <div class="container">
      <SecondHeader></SecondHeader>
      <div class="fuel-car">
          <div>
              <div> 
              <div class="text-one">Fuel up to ₦300 lesser below pump price</div>
              <div class="text-two"> With all the essentials you need out in the world, and nothing to limit your possibilities, here is everything Remis has to offer</div>
              </div>
              <img src="../assets/frame1.png" alt=""  class="car">
              <div id="num-two"> 
              <div class="num-two">3</div>
              <div class="num-text-two">Track your vechicle performance</div>
              </div>
          </div>
          
          <div class="car-card">
              <img src="../assets/frame6.png" alt="" />
          </div>

      </div> 
         <div class="fuel-car2">
          <div>
              <div> 
              <div class="text-one2">Fuel up to ₦300 lesser below pump price</div>
              <div class="text-two2"> With all the essentials you need out in the world, and nothing to limit your possibilities, here is everything Remis has to offer</div>
              </div>
              <img src="../assets/frame1.png" alt=""  class="car2">
              <div id="num-two2"> 
              <div class="num-two2">2</div>
              <div class="num-text-two2">Track your vechicle performance</div>
              </div>
          </div>
          
          <div class="car-card2">
              <img src="../assets/frame6.png" alt="" />
          </div>

      </div>  
      <div class="fuel-car3">
          <div>
              <div> 
              <div class="text-one3">Fuel up to ₦300 lesser below pump price</div>
              <div class="text-two3"> With all the essentials you need out in the world, and nothing to limit your possibilities, here is everything Remis has to offer</div>
              </div>
              <img src="../assets/frame1.png" alt=""  class="car3">
              <div id="num-two3"> 
              <div class="num-two3">1</div>
              <div class="num-text-two2">Track your vechicle performance</div>
              </div>
          </div>
          
          <div class="car-card3">
              <img src="../assets/frame2.png" alt="" />
          </div>

      </div> 
      <div class="save">
          <h1>Over ₦1,000,000 saves on subsidy</h1>
      </div>
       <div class="hand">
         <h2>Get More with Every Fill , Turn Every Drop into Value</h2>
         <p>Fuel smarter. Earn more. Drive better with Fuel Subsidy</p>
       </div>
       <div class="refer">
        <div class="phone-coin">
          <img src="../assets/Frame4.png" alt="">
        </div>
        <div class="refer-earn">
          <img src="../assets/refer.png" alt="">
        </div>
       </div>
        <!-- <div class="track-two">
              <div class="image">  
                <img src="../assets/Frame1.png" alt="" />
                   <div class="num-2">
                <span >2</span>
                Track your vechicle performance
            </div>
            </div>
              <img src="../assets/Frame6.png" alt="">          
        </div> -->
        <!-- <div class="fuel-price">
            <div class="fuel">
                <h2>Fuel up to #300 lesser below pump price</h2>
                <p>With all the essentials you need out in the world and nothing to limit your possibilities,
                    here is everything Remis has to offer.
                </p>
               <div class="image">
                 <img src="../assets/Frame1.png" alt=""/>
               </div>
                <div class="num-1">
                <span>1</span>
                Fuel subsidy is back
            </div>
            
            <div class="fuel-img">
                <img src="../assets/Frame2.png" alt="" >
            </div>
            </div>
        </div> -->
      
        
    </div>
</template>
<script>
import SecondHeader from './SecondHeader.vue';
export default{
    components:{
      SecondHeader
    }
}</script>
<style>
.container{
    background-color: #FFFFFF;
    height:2917px ;
    width: 1440px;
    position: absolute;
    top: 997px;
}
.fuel-car{
    background-color:#F1F8FF;
    border-radius: 26.82px;
    display: flex;
    width: 1161.02px;
   height: 605px;
   position: absolute;
   left: 139.49px;
   top: 321px;
}
.text-one{
    width: 390px;
    height: 120px;
    font-size: 38px;
    margin-top:98px ;
    margin-left: 96px;
}
.text-two{
    width: 366px;
    height: 87px;
    font-size: 18px;
    /* margin-top:15px ; */
    margin-left: 96px;
    /* background-color: blue; */
    text-align:justify;
    font-weight: 400;
    letter-spacing: -2%;
    line-height: 160%;
} 
.car{
    width: 149px;
    height: 114px;
    margin-top: 127px;
    margin-left: 22px;
}
#num-two{
    display: flex;
    align-items:center;
    gap:11.5px ;
    margin-top: 12px;
    margin-left: 21.07px;
}
.num-two{
    width: 38.32px;
    height: 38.32px;
    padding: 8px;
    text-align: center;
    background-color:#CBF5E5 ;
    border: 1px solid #FFFFFF;
    border-radius: 20px;
}
.num-text-two{
   width: 244px; 
   height: 29px;
   font-size: 17.24px;
   font-weight: 400;
}
.car-card img{
    width: 542.23px;
    height: 565.22px;
    margin-top: 12.4px;
    margin-left: 99.42px;
}
.fuel-car2{
    background-color:#F8FFF1;
    border-radius: 26.82px;
    display: flex;
    width: 1226.24px;
   height: 638.99px;
   position: absolute;
   left: 106px;
   top: 239.59px;
}
.text-one2{
    width: 390px;
    height: 120px;
    font-size: 38px;
    margin-top:98px ;
    margin-left: 96px;
}
.text-two2{
    width: 366px;
    height: 87px;
    font-size: 18px;
    /* margin-top:15px ; */
    margin-left: 96px;
    /* background-color: blue; */
    text-align:justify;
    font-weight: 400;
    letter-spacing: -2%;
    line-height: 160%;
} 
.car2{
    width: 149px;
    height: 114px;
    margin-top: 127px;
    margin-left: 22px;
}
#num-two2{
    display: flex;
    align-items:center;
    gap:11.5px ;
    margin-top: 39px;
    margin-left: 21.07px;
}
.num-two2{
    width: 38.32px;
    height: 38.32px;
    padding: 8px;
    text-align: center;
    background-color:#CBF5E5 ;
    border: 1px solid #FFFFFF;
    border-radius: 20px;
}
.num-text-two2{
   width: 244px; 
   height: 29px;
   font-size: 17.24px;
   font-weight: 400;
}
.car-card2 img{
    width: 542.23px;
    height: 565.22px;
    margin-top: 36.4px;
    margin-left: 130.42px;
} 

.fuel-car3{
    background-color:#F5F5F5;
    border-radius: 26.82px;
    display: flex;
    width: 1280px;
   height: 667px;
   position: absolute;
   left: 80.11px;
   top: 154.5px;
}
.text-one3{
    width: 390px;
    height: 120px;
    font-size: 38px;
    margin-top:98px ;
    margin-left: 96px;
}
.text-two3{
    width: 366px;
    height: 87px;
    font-size: 18px;
    /* margin-top:15px ; */
    margin-left: 96px;
    /* background-color: blue; */
    text-align:justify;
    font-weight: 400;
    letter-spacing: -2%;
    line-height: 160%;
} 
.car3{
    width: 149px;
    height: 114px;
    margin-top: 127px;
    margin-left: 22px;
}
#num-two3{
    display: flex;
    align-items:center;
    gap:11.5px ;
    margin-top: 65px;
    margin-left: 21.07px;
}
.num-two3{
    width: 38.32px;
    height: 38.32px;
    padding: 8px;
    text-align: center;
    background-color:#CBF5E5 ;
    border: 1px solid #FFFFFF;
    border-radius: 20px;
}
.num-text-two3{
   width: 244px; 
   height: 29px;
   font-size: 17.24px;
   font-weight: 400;
}
.car-card3 img{
    width: 566px;
    height: 590px;
    margin-top: 36.4px;
    margin-left: 180.42px;
}
.save h1{
  width: 988px;
  height: 232px;
  position: absolute;
  top: 1042px;
  left: 225.85px;
  font-size: 80px;
  text-align: center;
  color:#0C1312;
}
.hand{
  width: 1440px;
  height: 736px;
  position: absolute;
  top: 1377px;
  left: 0.03px;
  background-image:url(../assets/hand.png) ;
  background-size: cover;
  
}
.hand h2{
  font-size: 56px;
  font-weight: 600;
  width: 559.22px;
  height: 252px;
  margin-top:180.84px ;
  margin-left:80px ;
  
}
.hand p{
  width:509.68px ;
  height: 28px;
  margin-left:80px ;
  margin-top: 57px;
}
.phone-coin img{
    width:629px ;
    height: 590px;
    position: absolute;
    top:2193px ;
    left:80px;

}
.refer-earn img{
  width:630px;
  height: 590px;
  background-color: #F5F5F5;
   position: absolute;
  top: 2193px; 
  left: 730.03px;
  border-radius: 20px;
}


</style>