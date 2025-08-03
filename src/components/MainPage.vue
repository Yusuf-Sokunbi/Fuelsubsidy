<template>
    <div class="main-page">
    <Header></Header>
    <Section1></Section1>

    </div>
</template>

<script>
import Header from './Header.vue';
import Section1 from './Section1.vue';
export default{
components:{
    Header,
    Section1
}
}
</script>

<style>
.main-page{
    position: relative;
    width: 1440px;
    height: auto;
    background-color: blue;
    
}
</style>