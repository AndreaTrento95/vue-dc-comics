<template>
  <main>
      <div class="container">

         <ComicsComp
            v-for="(comic, index) in comics"
            :key="index"
          />

      </div>
      
  </main>
</template>

<script>

import comics from '@/assets/data/dc-comics.js'
import ComicsComp from '@/components/ComicsComp.vue'


export default {
    name: 'MainComp',
    components:{
        ComicsComp
    },
    data(){
        return {
            comics
        }
    }
}
</script>


<style lang="scss" scoped>
    main {
        background-color: black;
        height: 100px;
        .container{
            display: flex;
        }
        
        
    }
</style>