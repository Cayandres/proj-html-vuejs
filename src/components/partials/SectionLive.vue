<script>
export default {
  name:'SectionLive'
}
</script>

<template>
  <div class="container-all-width">
    <div class="container-opaco">

      <div class="container">
        <div class="row">
          
          <div class="col">
            <div class="live-thumb">
              <img src="../../assets/v-1.png" alt="img-thumb">
              <div class="video-area">
                <div class="circle">
                  <a href="#" class="video"><svg class="svg-inline--fa fa-play white" aria-hidden="true" focusable="false" data-prefix="fas" data-icon="play" role="img" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 384 512" data-fa-i2svg=""><path fill="currentColor" d="M361 215C375.3 223.8 384 239.3 384 256C384 272.7 375.3 288.2 361 296.1L73.03 472.1C58.21 482 39.66 482.4 24.52 473.9C9.377 465.4 0 449.4 0 432V80C0 62.64 9.377 46.63 24.52 38.13C39.66 29.64 58.21 29.99 73.03 39.04L361 215z"></path></svg></a>
                </div>
                <span>
                  Call Of Duty
                </span>
              </div>
            </div>
          </div>
  
          <div class="col live-streming-content">
            <div class="section-header">
              <span class="subtitle">
                live Streaming
              </span>
              <h1 class="title">
                Checkout Our Live Streaming
              </h1>
              <div class="buttons">
                <button class="arrow-right"><a class="" href="#">
                  <svg class="svg-inline--fa fa-arrow-left-long" aria-hidden="true" focusable="false" data-prefix="fas" data-icon="arrow-left-long" role="img" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 512 512" data-fa-i2svg=""><path fill="currentColor" d="M9.375 233.4l128-128c12.5-12.5 32.75-12.5 45.25 0s12.5 32.75 0 45.25L109.3 224H480c17.69 0 32 14.31 32 32s-14.31 32-32 32H109.3l73.38 73.38c12.5 12.5 12.5 32.75 0 45.25c-12.49 12.49-32.74 12.51-45.25 0l-128-128C-3.125 266.1-3.125 245.9 9.375 233.4z"></path></svg></a> 
                </button>
                <button class="active white"><a class="" href="#">
                  <svg class="svg-inline--fa fa-arrow-right-long white" aria-hidden="true" focusable="false" data-prefix="fas" data-icon="arrow-right-long" role="img" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 512 512" data-fa-i2svg=""><path fill="currentColor" d="M502.6 278.6l-128 128c-12.51 12.51-32.76 12.49-45.25 0c-12.5-12.5-12.5-32.75 0-45.25L402.8 288H32C14.31 288 0 273.7 0 255.1S14.31 224 32 224h370.8l-73.38-73.38c-12.5-12.5-12.5-32.75 0-45.25s32.75-12.5 45.25 0l128 128C515.1 245.9 515.1 266.1 502.6 278.6z"></path></svg></a> 
                </button>
              </div>
            </div>
            <div class="cards">
              <div class="card">
                <img src="../../assets/v-small1.png" alt="img">
                <h4>Call of Duty</h4>
                <p>Gioco sparatutto ambientato nella seconda guerra mondiale, sei pronto a farne parte?</p>
              </div>
              <div class="card">
                <img src="../../assets/v-small2.png" alt="img">
                <h4>Call of Duty</h4>
                <p>Gioco sparatutto ambientato nella seconda guerra mondiale, sei pronto a farne parte?</p>
              </div>
            </div>
  
          </div>
        </div>
      </div>
    </div>
  </div>  
</template>

<style lang="scss" scoped>
@use '../../scss/partials/vars.scss' as*; 
@use '../../scss/main.scss' as*;

.container-all-width{
  position: relative;
  height: 100vh;
  background-image: url(../../assets/v-bg.png);
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
    left: 175px;
    height: 100%;
    z-index: 10;
    .row{
      display: flex;
      align-items: center;
      height: 100%;
      color: $white;
      .col{
      justify-content: center;
        width: 50%;
        .live-thumb{
          position: relative;
          img{
            width: 100%;
          }
          .video-area{
            position: absolute;
            top: 50%;
            left: 50%;
            transform: translate(-50%, -50%);
            color: $white;
            .circle{
              padding: 30px 35px;
              background-color: $green;
              border-radius: 50%;
              margin: 10px 0;
              #play{
                display: block;
                height: 10px;
              }
            }
          }
        }
      }
      .live-streming-content{
        position: relative;
        margin-left: 20px;
        .title{
          padding: 20px 0;
          font-size: 3rem;
        }
        .buttons{
          position: absolute;
          right: 0px;
          top: 100px;
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
        .cards{
          display: flex;
          .card{
            width: 50%;
            margin-left: 10px;
            img{
              width: 100%;
            }
            h4{
              font-weight: 800;
              padding: 10px 0;
            }
        }
        }
      }
    }
  }
}
</style>