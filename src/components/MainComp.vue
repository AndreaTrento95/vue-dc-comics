<template>
  <main>
      <div class="container">

         <ComicsComp
            v-for="(comic, index) in comics"
            :key="index"
            :single='comic'
          />

          <div class="btn">
              <button>LOAD MORE</button>
          </div>

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

// importo le variabili
@import '@/assets/style/vars';

    main {
        background-color: black;
        .container{
            display: flex;
            flex-wrap: wrap;
            padding: 30px;
            .btn{
                width: 100%;
                display: flex;
                justify-content: center;
                align-items: center;
                margin-top: 40px;
                button{
                    border: none;
                    padding: 10px 40px;
                    background-color: $brand-color;
                    color: white;
                    cursor: pointer;
                }
            }
        }
        
        
    }
</style>