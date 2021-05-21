<template>
  <header >
      <div class="container wrapper">

          <div class="logo">
              <img src="../assets/img/dc-logo.png" alt="">
          </div>

          <div class="menu">
              <ul>

                  <li
                    v-for="(link, index) in menu"
                    :key="index"
                  >
                      <a :class="{'active' : link.current }"  href="#"><h5>{{ link.text }}</h5></a>
                  </li>
            
                 
              </ul>
          </div>

      </div>
      
  </header>
</template>

<script>
export default {
    name: 'HeaderComp',
    props:{
        menu: Array
    }
}
</script>


<style lang="scss" scoped>

@import '@/assets/style/vars.scss';

header{
    width: 100%;
    height: 70px;
    .wrapper{
        height: 70px;
        display: flex;
        
        align-items: center;
        .logo{
            flex-basis: 90%;
            height: 60px;
            img{
                height: 100%;
            }
        }
    }
}
header .wrapper .menu{
    flex-basis: 80%;
}
header .wrapper .menu ul{
    height: 100%;
    display: flex;
    align-items: center;
    list-style: none;
    li{
        display: inline-block;
        height: 100%;
        margin: 5px;
        a{
            text-decoration: none;
            h5{
                text-transform: uppercase;
                font-size: 0.6em;
                color: black;
            }
        }
        &:hover,
        &.active{
        border-bottom: 2px solid $brand-color;
    }
    }
    
}


</style>