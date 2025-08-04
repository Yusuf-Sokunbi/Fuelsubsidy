<template>
<div id="main">
  <MainPage></MainPage>
   <SecondPage></SecondPage>
  
</div>

</template>

<script>
import MainPage from './components/MainPage.vue'
import SecondPage from './components/SecondPage.vue';

export default{
components:{
  MainPage,
  SecondPage
}
}

</script>

<style>
*{
  padding: 0;
  margin: 0;
  box-sizing: border-box;
}
 #main{
  position: relative;
 }
</style>
