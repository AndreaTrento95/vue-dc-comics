<template>
  <footer>
      <div class="container wrapper">
          <div class="cols">
              <div class="col">
                  <h4>DC COMICS</h4>
                  <ul>
                      <li>
                          <a href="#">Characters</a>
                      </li>
                      <li>
                          <a href="#">Characters</a>
                      </li>
                      <li>
                          <a href="#">Characters</a>
                      </li>
                      <li>
                          <a href="#">Characters</a>
                      </li>
                      <li>
                          <a href="#">Characters</a>
                      </li>
                      <li>
                          <a href="#">Characters</a>
                      </li>
                      <li>
                          <a href="#">Characters</a>
                      </li>
                      
                  </ul>
              </div>
              <div class="col">
                  <h4>DC</h4>
                  <ul>
                      <li>
                          <a href="#">Characters</a>
                      </li>
                      <li>
                          <a href="#">Characters</a>
                      </li>
                      <li>
                          <a href="#">Characters</a>
                      </li>
                      <li>
                          <a href="#">Characters</a>
                      </li>
                      <li>
                          <a href="#">Characters</a>
                      </li>
                      <li>
                          <a href="#">Characters</a>
                      </li>
                      <li>
                          <a href="#">Characters</a>
                      </li>
                      <li>
                          <a href="#">Characters</a>
                      </li>
                      <li>
                          <a href="#">Characters</a>
                      </li>
                      
                  </ul>
              </div>
              <div class="col">
                  <h4>SITES</h4>
                  <ul>
                      <li>
                          <a href="#">Characters</a>
                      </li>
                      <li>
                          <a href="#">Characters</a>
                      </li>
                      <li>
                          <a href="#">Characters</a>
                      </li>
                      <li>
                          <a href="#">Characters</a>
                      </li>
                      <li>
                          <a href="#">Characters</a>
                      </li>
                  </ul>
              </div>
              <div class="col">
                  <h4>SHOP</h4>
                  <ul>
                      <li>
                          <a href="#">Characters</a>
                      </li>
                      <li>
                          <a href="#">Characters</a>
                      </li>
                  </ul>
              </div>

          </div>
          <div class="img"></div>
      </div>

      <div class="bottom-line">
          <div class="container bottom-wrapper">

              <button>
                  SIGN-Up NOW
              </button>

                <div class="social">
                    <h4>FOLLOW US</h4>
                    <i class="fas fa-facebook-f"></i>
                </div>

          </div>
      </div>

  </footer>
  
</template>

<script>
export default {
    name: 'FooterComp'
}
</script>

<style lang="scss" scoped>
footer{
    height: 500px;
    width: 100%;
    background-image: url('../assets/img/footer-bg.jpg');
    .wrapper{
        display: flex;
        .img{
            width: 60%;
            height: 100%;
            background-image: url('../assets/img/dc-logo-bg.png');
            background-size: contain;
        }
        .cols{
            width: 35%;
            display: flex;
            flex-wrap: wrap;
            margin-top: 30px;
            .col{
                margin-right: 30px;
                h4{
                    color: white;
                    margin-bottom: 10px;
                }
                li{
                    margin-bottom: 5px;
                    font-size: 0.8em;
                    a{
                        color: gray;
                    }
                }
            }
        }
    }
}

footer{
    .bottom-line{
        width: 100%;
        height: 70px;
        background-color: gray;
        margin-top: 124px;
        .bottom-wrapper{
            height: 70px;
            display: flex;
            justify-content: space-between;
            align-items: center;
            button{
                padding: 8px 5px;
            }
        }
        
    }
}

</style>