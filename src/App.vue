<template>
<div>
  <NavBar :Logo="logo" :Alt="alt"/>
  <router-view/>
  <Footer/>
</div>
</template>

<script>
import NavBar from './components/NavBar.vue';
import Footer from './components/Footer.vue';
import Logo from '../public/img/logo.png';

export default {
    components:{
      NavBar,
      Footer
    },
    data(){   
      return{ 
        logo: Logo,
        alt: 'Make Your Burger'
      } 
    }
}
</script>
<style>
 *{
   font-family: Helvetica;
   margin: 0;
   padding: 0;
   box-sizing: border-box;
 }

 .main-container{
   margin: 50px;
   min-height: 250px;
 }
 h1{
   text-align: center;
   font-size: 40px;
   margin-bottom: 30px;
   color: #222;
 }
</style>
