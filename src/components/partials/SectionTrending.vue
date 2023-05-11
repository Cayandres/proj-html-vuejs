<script>
export default {
  name: 'SectionTrending'
}
</script>

<template>
  <div class="container-all-widht">
    <div class="container-opaco">

      <div class="container">
        <span class="subtitle">Tranding games</span>
        <h2 class="white">Choose Who Is The Best In World! </h2>
        <div class="buttons">
          <button class="arrow-right"><a class="" href="#">
            <svg class="svg-inline--fa fa-arrow-left-long" aria-hidden="true" focusable="false" data-prefix="fas" data-icon="arrow-left-long" role="img" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 512 512" data-fa-i2svg=""><path fill="currentColor" d="M9.375 233.4l128-128c12.5-12.5 32.75-12.5 45.25 0s12.5 32.75 0 45.25L109.3 224H480c17.69 0 32 14.31 32 32s-14.31 32-32 32H109.3l73.38 73.38c12.5 12.5 12.5 32.75 0 45.25c-12.49 12.49-32.74 12.51-45.25 0l-128-128C-3.125 266.1-3.125 245.9 9.375 233.4z"></path></svg></a> 
          </button>
        <button class="active white"><a class="" href="#">
          <svg class="svg-inline--fa fa-arrow-right-long white" aria-hidden="true" focusable="false" data-prefix="fas" data-icon="arrow-right-long" role="img" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 512 512" data-fa-i2svg=""><path fill="currentColor" d="M502.6 278.6l-128 128c-12.51 12.51-32.76 12.49-45.25 0c-12.5-12.5-12.5-32.75 0-45.25L402.8 288H32C14.31 288 0 273.7 0 255.1S14.31 224 32 224h370.8l-73.38-73.38c-12.5-12.5-12.5-32.75 0-45.25s32.75-12.5 45.25 0l128 128C515.1 245.9 515.1 266.1 502.6 278.6z"></path></svg></a> 
        </button>
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
                  <img class="playButton" src="../../assets//image (9).svg" alt="">
              </div>
            </div>
            <div class="tag-green">New</div>
          </div>
          <div class="card">
            <img src="../../assets/protfolio4.png" alt="#">
            <div class="info">
              <div class="description">
                <h3>Assassin's Creed</h3>
                <span>Gioco basato sul medio evo a Firenze</span>
              </div>
              <div class="button">
                  <img class="playButton" src="../../assets//image (9).svg" alt="">
              </div>
            </div>
            <div class="tag-green">New</div>
          </div>
          <div class="card">
            <img src="../../assets/protfolio3.png" alt="#">
            <div class="info">
              <div class="description">
                <h3>Assassin's Creed</h3>
                <span>Gioco basato sul medio evo a Firenze</span>
              </div>
              <div class="button">
                  <img class="playButton" src="../../assets//image (9).svg" alt="">
              </div>
            </div>
            <div class="tag-green">New</div>
          </div>
          <div class="card">
            <img src="../../assets/protfolio2.png" alt="#">
            <div class="info">
              <div class="description">
                <h3>Assassin's Creed</h3>
                <span>Gioco basato sul medio evo a Firenze</span>
              </div>
              <div class="button">
                  <img class="playButton" src="../../assets//image (9).svg" alt="">
              </div>
            </div>
            <div class="tag-green">New</div>
          </div>
  
        </div>
      </div>
    </div>
  </div>
</template>


<style lang="scss" scoped>
@use '../../scss/partials/vars.scss' as*;
.container-all-widht{
  height: 100vh;
  background-image: url(../../assets/protfolio-vector.png);
  background-color: $blueDark;
  position: relative;
  .container-opaco{
    &::after{
      position: absolute;
      content: "";
      top: 0;
      left: 0;
      right: 0;
      bottom: 0;
      background: rgba(26, 25, 53, 0.5);
    }
  }
  .container{
    position: absolute;
    z-index: 10;
    left: 175px;
    padding: 100px 0;
    height: 2px;
    h2{
      font-size: 3rem;
      width: 40%;
      padding: 20px 0;
    }
    .buttons{
    position: absolute;
    right: 0px;
    top: 192px;
    button{
      margin: 0 5px;
      height: 50px;
      width: 50px;
      padding: 10px;
      border-radius: 50%;
      line-height: 10px;
      border: none;
      color: black;
      svg{
        height: 20px;
      }
    }
  }
    .cards-container{
      display: flex;
      justify-content: space-between;
      .card{
        position: relative;
        width: calc(100%/4.3);
        background-color:$blueDark;
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
            background-color: $greenLight;
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
            background-color: $greenLight;
            color: $blue;
            padding: 5px 10px;
          }
      }
    }
  }
}
</style>