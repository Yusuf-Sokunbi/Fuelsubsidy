<template>
    <div id="section">
        <div class="smart">
            <h1>
                Smart Fueling.
                Real Savings.
            </h1>
            <div class="scan">
                <img src="../assets/QR.png" alt="">
                <p>Scan to download our App on the Play store and App store</p>
            </div>
        </div>
        <div id="img">
            <img id="one" src="../assets/Circle1.png" alt="">
             <img id="two" src="../assets/Circle2.png" alt="">
        </div>
        <div class="phone">
            <div><img src="../assets/Phone.png" alt=""></div>
        </div>
        <div class="text">
          <p>
            With all the essentials you need out in the world, and nothing to limit 
            your possibilities, here is everything Remis has to offer
          </p>

          <button>scroll <img src="../assets/arrow-up.png" alt=""></button>
        </div>
    </div>
</template>
<style>
#section{
    display: flex;
    background-color: #000;
}
/* .smart{
    position: absolute;

} */
.smart h1{
    width: 383px;
    height: 168px;
    font-size: 56px;
    position: absolute;
    top: 279.57px;
    left: 80px;
    }
    .scan{
    display: flex;
    align-items: center;
    gap: 8px;
    width: 345px;
    height: 99px;
    position: absolute;
    top: 522px;
    left: 80.08px;
    background-color:#548688 ;
    border-radius: 16px;
}


.scan img{
 height: 75px;   
 width: 75px;
 padding: 12px;
 background-color: #000;
 border-radius: 16px;
}
.scan p{
    font-size: 16px;
    height:48px ;
    width: 222px;
}
.phone{
    width:400px ;
    height: 815.7px;
    position: absolute;
    top: 79.97px;
    left: 320.11px;
}
.text button{
   position: absolute;
   top:745px ;
   left: 1253.58px;
   background-color: #2D2D2D;
   color:#E6EDED ;
   padding: 8px 20px;
   border-radius: 20px;
   border: 1px solid #ffffff;



}
.text p{
    font-size: 18px;
    width: 366px;
    height: 87px;
     position: absolute;
     top: 577px;
     left: 994.08px;
}
#img #one{
 width: 948.57px;
 height: 384.43px;
 position: absolute;
 top: 612.57px;
 left: 246.27px;
 border: 1px solid #fff;
}
#img #two{
    width: 1352px;
    height: 583.07px;
    position: absolute;
    top:413.93px ;
    left: 44.55px;
}
</style>