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
            <img src="../../assets/1.png" alt="#">
            <img class="image-position" src="../../assets/1.png" alt="#">
          </div>
          <div class="description">
            <h3>Ninja Warrior Gaming</h3>
            <div class="square-info">
              <div class="socials">
                <img src="../../assets/image (13).svg" alt="">
                <img src="../../assets/image (14).svg" alt="">
              </div>
              <span>  10:45 </span>
              <span>10 ottobre, 2032</span>
              <button>ciao</button>
            </div>


          </div>
        </div>
      </div>
    </div>
  </div>
</template>


<style lang="scss" scoped>
.container-all-widht{
  min-height: 100vh;
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
        width: calc(100%/3.3);
        background-color: #202046;
        border-radius: 10px;
        overflow: hidden;
        .image-card{
          position: relative;
          border-radius: 10px;
          margin: 25px;
          padding: 30px 60px;
          background-color: rgba(0, 0, 0, 0.272);
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
        span{
          padding: 5px 0;
          display: block;
          font-weight: bold;
          font-size: 1rem;
        }
        h3{
          font-size: 2rem;
        }
        .square-info{
            width:100%;
            display: flex;
            flex-direction: column;
            text-align: center;
            border-radius: 10px;
            align-items: center;
            span{
              &:first-child{
                padding: 5px;
                font-size: 1.5rem;
              }
              font-weight: bold;
            }
            .socials{
              padding-top: 5px;
              img{
                background-color: green;
                padding: 10px;
                margin: 10px;
                height: 50px;
                width: 50px;
                border-radius: 50%;
              }
            }
            button{
              width: 40px;
              margin: 40px 0;
            }
          }
        
      }
    }
  }
}
}
</style>