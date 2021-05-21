<template>
  <div id="app">
    <HeaderComp :menu="links" />
    <MainComp />
    <FooterComp />
  </div>
</template>

<script>
import HeaderComp from '@/components/HeaderComp.vue'
import MainComp from '@/components/MainComp.vue'
import FooterComp from '@/components/FooterComp.vue'


export default {
  name: "App",
  data(){
    return{
      links: [
        {
          text: 'characters',
          current: false
        },
        {
          text: 'comics',
          current: true
        },
        {
          text: 'movies',
          current: false
        },
        {
          text: 'tv',
          current: false
        },
        {
          text: 'games',
          current: false
        },
        {
          text: 'collectibiles',
          current: false
        },
        {
          text: 'videos',
          current: false
        },
        {
          text: 'fans',
          current: false
        },
        {
          text: 'news',
          current: false
        },
        {
          text: 'shop',
          current: false
        }
      ]
    }
  },
  components: {
    HeaderComp,
    MainComp,
    FooterComp,
  },
};
</script>

<style lang="scss">
 // GENERAL
 * {
   padding: 0;
   margin: 0;
   box-sizing: border-box;
 }

 .container{
   width: 1000px;
   margin: 0 auto;
 }

 ul{
   list-style: none;
 }

 a{
   text-decoration: none;
 }
  
</style>
