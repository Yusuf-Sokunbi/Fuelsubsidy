<template>
    <div id="page2">
    <div class="page2">
        <!-- <SecondHeader></SecondHeader> -->
    <Section2></Section2>
    </div>

    </div>
</template>
<script>
import SecondHeader from './SecondHeader.vue';
import Section2 from './Section2.vue';
export default{
    components:{
     SecondHeader,
     Section2
    }
}
</script>
<style>
#page{
    background-color: blue;
    width: 1440px;
    height: 2917px;
    position: absolute;
    top: 997px;
}
.page2{
    position: relative;
}

</style>
