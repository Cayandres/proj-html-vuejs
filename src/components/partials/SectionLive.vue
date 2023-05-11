<script>
export default {
  name:'SectionLive'
}
</script>

<template>
  <div class="container-all-width">
    <div class="container">
      <div class="row">
        
        <div class="col">
          <div class="live-thumb">
            <img src="../../assets/v-1.png" alt="img-thumb">
            <div class="video-area">
              <div class="circle">
                <a href="#" class="video"><img id="play" src="../../assets/image (9).svg" alt="play"></a>
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
              <button>c</button>
              <button>a</button>
            </div>
          </div>
          <div class="cards">
            <div class="card">
              <img src="../../assets/v-1.png" alt="img">
              <h4>Call of Duty</h4>
              <p>Gioco sparatutto ambientato nella seconda guerra mondiale, sei pronto a farne parte?</p>
            </div>
            <div class="card">
              <img src="../../assets/v-1.png" alt="img">
              <h4>Call of Duty</h4>
              <p>Gioco sparatutto ambientato nella seconda guerra mondiale, sei pronto a farne parte?</p>
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
  height: 100vh;
  background-image: url(../../assets/v-bg.png);
  .container{
    height: 100%;
    .row{
      display: flex;
      align-items: center;
      height: 100%;
      color: white;
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
            color: white;
            .circle{
              padding: 40px;
              background-color: $green;
              border-radius: 50%;
              #play{
                display: block;
                margin: 0 auto;
                width: 15px;
              }
            }
          }
        }
      }
      .live-streming-content{
        position: relative;
        margin-left: 20px;

        .subtitle{
          color: $green;
        }
        .title{
          padding: 20px 0;
          font-size: 3rem;
        }
        .buttons{
          position: absolute;
          right: 0px;
          top: 100px;
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