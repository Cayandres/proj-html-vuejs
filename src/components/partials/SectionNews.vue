<script>
export default {
  name: 'SectionUpcoming'
}
</script>

<template>
  <div class="container-all-widht">
    <div class="container">
      <span>Tranding games</span>
      <h2>Choose who is the best in the world!</h2>
      <div class="buttons">
        <button>a</button>
        <button>b</button>
      </div>
      <div class="cards-container">
        <div class="card">
          <div class="image-card">
            <img src="../../assets/b1.png" alt="#">
          </div>
          <div class="description">
            <h3>Ninja Warrior Gaming</h3>
            <div class="square-info">
              <div class="socials">
                <div>
                  <img src="../../assets/image (13).svg" alt="">
                  <span>By admin</span>
                </div>
                <div>
                  <img src="../../assets/image (21).svg" alt="">
                  <span>Octobre 2022</span>
                </div>
              </div>
            </div>
            <button>ciao</button>                


          </div>
        </div>
        <div class="card">
          <div class="image-card">
            <img src="../../assets/b1.png" alt="#">
          </div>
          <div class="description">
            <h3>Ninja Warrior Gaming</h3>
            <div class="square-info">
              <div class="socials">
                <div>
                  <img src="../../assets/image (13).svg" alt="">
                  <span>By admin</span>
                </div>
                <div>
                  <img src="../../assets/image (21).svg" alt="">
                  <span>Octobre 2022</span>
                </div>
              </div>
            </div>
            <button>ciao</button>                


          </div>
        </div>
        <div class="card">
          <div class="image-card">
            <img src="../../assets/b1.png" alt="#">
          </div>
          <div class="description">
            <h3>Ninja Warrior Gaming</h3>
            <div class="square-info">
              <div class="socials">
                <div>
                  <img src="../../assets/image (13).svg" alt="">
                  <span>By admin</span>
                </div>
                <div>
                  <img src="../../assets/image (21).svg" alt="">
                  <span>Octobre 2022</span>
                </div>
              </div>
            </div>
            <button>ciao</button>                


          </div>
        </div>
        <div class="card">
          <div class="image-card">
            <img src="../../assets/b1.png" alt="#">
          </div>
          <div class="description">
            <h3>Ninja Warrior Gaming</h3>
            <div class="square-info">
              <div class="socials">
                <div>
                  <img src="../../assets/image (13).svg" alt="">
                  <span>By admin</span>
                </div>
                <div>
                  <img src="../../assets/image (21).svg" alt="">
                  <span>Octobre 2022</span>
                </div>
              </div>
            </div>
            <button>ciao</button>                


          </div>
        </div>
      </div>
    </div>
  </div>
</template>


<style lang="scss" scoped>
.container-all-widht{
  height: 100vh;
  background-color: #3d3d62;
  .container{
    position: relative;
    padding: 100px 0;
    height: 1000px;
    h2{
      font-size: 3rem;
      width: 50%;
    }
    .buttons{
      position: absolute;
      right: 30px;
      top: 197px;

    }
    .cards-container{
      display: flex;
      justify-content: space-between;
      .card{
        padding: 0px;
        width: calc(100%/4.3);
        background-color: #202046;
        border-radius: 10px;
        overflow: hidden;
        .image-card{
          .image-position{
            position: absolute;
            top: -10px;
            right: 0px;
            opacity: 0.1;
            width: 250px;
          }
        img{
          width: 100%;
        }
      }
      
      .description{
        text-align: center;
        margin: 10px;
        color: white;
        h3{
          font-size: 1.5rem;
        }
        
        .socials{
        padding-top: 5px;
        display: flex;
        div{
          height: 30px;
          display: flex;
          align-items: center;
          &:first-child{
            border-right: 1px solid green;
            padding-right: 20px;
          }
          img{
                  padding: 10px;
                  margin: 10px;
                  width: 40px;
                }
                span{
                  font-size: 10px;
                }
              }
            }
            button{
              width: 40px;
              margin: 10px 0;
            }

        
      }
    }
  }
}
}
</style>