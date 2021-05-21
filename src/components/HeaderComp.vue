<template>
  <header >
      <div class="container wrapper">

          <div class="logo">
              <img src="../assets/img/dc-logo.png" alt="">
          </div>

          <div class="menu">
              <ul>
                  <li>
                      <a href="#"><h5>Characters</h5></a>
                  </li>
                  <li>
                      <a href="#"><h5>Characters</h5></a>
                  </li>
                  <li >
                      <a class="active" href="#"><h5>Characters</h5></a>
                  </li>
                  <li>
                      <a href="#"><h5>Characters</h5></a>
                  </li>
                  <li>
                      <a href="#"><h5>Characters</h5></a>
                  </li>
                  <li>
                      <a href="#"><h5>Characters</h5></a>
                  </li>
                  <li>
                      <a href="#"><h5>Characters</h5></a>
                  </li>
                  <li>
                      <a href="#"><h5>Characters</h5></a>
                  </li>
                  <li>
                      <a href="#"><h5>Characters</h5></a>
                  </li>
                  <li>
                      <a href="#"><h5>Characters</h5></a>
                  </li>
                 
              </ul>
          </div>

      </div>
      
  </header>
</template>

<script>
export default {
    name: 'HeaderComp'
}
</script>


<style lang="scss" scoped>
header{
    width: 100%;
    height: 70px;
    .wrapper{
        height: 70px;
        display: flex;
        justify-content: space-between;
        align-items: center;
        .logo{
            height: 60px;
            img{
                height: 60px;
            }
        }
    }
}
header .wrapper .menu ul{
    display: flex;
    list-style: none;
    li{
        height: 100%;
        margin: 5px;
        
        a{
            display: inline-block;
            text-decoration: none;
            h5{
                text-transform: uppercase;
                font-size: 0.6em;
                color: black;
            }
        }
        a:hover,
        a.active{
        margin-bottom: 2px solid blue;
    }
    }
    
}


</style>