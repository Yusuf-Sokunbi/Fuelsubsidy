<template>
    <div>
        <nav class="navbar">
            <div id="fuel"><img src="../assets/fuel-icon.png" alt=""/>FuelSubsidy</div>
            <div id="location"><img src="../assets/location.png" alt=""/>Find a station</div>
        </nav>
    </div>
</template>

<style>
.navbar{
    background-color:#000;
    width: 1280px;
    height: 48px;
    display: flex;
    justify-content: space-between;
    position: absolute;
    left: 80px;
    color: #fff;
}

#fuel{
    font-size: 22.04px;
    width:160 41px ;
    height: 36.74px;
    gap: 3.67px;
    display: flex;
    align-items: center;

    
}
#fuel img{
        width: 36.74px;
        height: 36.74px;
        
    /* align-items: center; */
    }
    #location{
        padding: 16px 24px;
        background-color: #B4DCDD;
        gap: 4px;
        border-radius: 40px;
        display: flex;
    align-items: center;
    }
#location img{
        width: 16px;
        height: 16px;
    }
</style>