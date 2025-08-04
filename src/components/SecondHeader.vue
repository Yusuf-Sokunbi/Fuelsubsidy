<template>
    <div>
        <nav class="navbar2">
            <div id="fuel2"><img src="../assets/fuel-icon.png" alt=""/>FuelSubsidy</div>
          <div id="btn-icon">  
            <div id="location2"><img src="../assets/location.png" alt=""/>Find a station</div>
            <div id="download"><img src="../assets/scanning.png" alt="">Download app</div>
        </div>
        </nav>
    </div>
</template>

<style scoped>
.navbar2{
    background-color:#191D21;
    width: 598px;
     height: 56px; 
     padding: 12px;
     gap: 10px;
     display: flex;
     align-items: center;
     justify-content: space-between;
     border-radius: 100px;
     position: absolute;
     top: 14px;
     left: 411px;
    
     
    
}

#fuel2{
    font-size: 20px;
    width:144 67px ;
    height: 32.74px;
    gap: 3.67px;
    display: flex;
    align-items: center;
    color:#fff;

    
}
#fuel2 img{
        width: 32px;
        height: 32px;
        border-radius: 9.6px;
        border: 1.14px solid #B4DCDD;
        
    /* align-items: center; */
    }

    #btn-icon{
        display: flex;
        align-items: center;
        gap: 12px;
    }
    #location2, #download{
        padding: 8px;
        background-color: #B4DCDD;
        gap: 4px;
        border-radius: 40px;
        display: flex;
    align-items: center;
    }
#location2 img, #download img{
        width: 16px;
        height: 16px;
    }
</style>