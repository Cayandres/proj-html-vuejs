<script>
export default {
  name: 'SectionTrending'
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
          <img src="../../assets/protfolio1.png" alt="#">
          <div class="info">
            <div class="description">
              <h3>Assassin's Creed</h3>
              <span>Gioco basato sul medio evo a Firenze</span>
            </div>
            <div class="button">
              <a href="°">
                <img class="playButton" src="../../assets//image (9).svg" alt="">
              </a>
            </div>
          </div>
          <div class="tag-green">New</div>
        </div>

      </div>
    </div>
  </div>
</template>


<style lang="scss" scoped>
.container-all-widht{
  height: 100vh;
  .container{
    position: relative;
    padding: 100px 0;
    height: 2px;
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
        position: relative;
        width: calc(100%/4.3);
        background-color: blue;
        color: white;
        img{
          width: 100%;
          aspect-ratio: 1/1;
        }
        .info{
          width: 100%;
          display: flex;
          align-items: center;
          padding: 10px;

          .button{
            width: 80px;
            height: 60px;
            line-height: 70px;
            background-color: green;
            text-align: center;
            border-radius: 50%;
            margin-left: 8px;
            
            .playButton{
              height: 20px;
            }
          }
        }
          .tag-green{
            position: absolute;
            top: 0;
            background-color: green;
            padding: 5px 10px;
          }
      }
    }
  }
}
</style>