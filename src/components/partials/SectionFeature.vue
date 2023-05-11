<script>
export default {
  name:'SectionFeature'
}
</script>

<template>
  <div class="container-all-width">
    <div class="container">
      <div class="row">
        <div class="col description">
          <h4>Our Extreme Feature</h4>
          <h2 id="title">The Best Gaming Arena On The World! </h2>
          <p>Nulla quis lorem ut libero malesuada feugiat. Vivamus magna justo, lacinia eget consectetur sed, at tellus. Cras ultricies ligula sed magna ivamus magna justo, dictum porta. sapien massa, convallis. </p>
        </div>
        <div class="col cards">
          <div class="card active-bg">
            <div class="feature-items">
              <div class="feature-thumb">
                <img src="../../assets/feature1.png" alt="f-img">
              </div>
              <div class="feature-cntent">
                <h2 class="title">
                  Live Streaming
                </h2>
                <p>
                  Nulla porttitor accumsan tincidunt. Pellentesque in.
                </p>
              </div>
            </div>

          </div>
          <div class="card">
            <div class="feature-items">
              <div class="feature-thumb">
                <img src="../../assets/feature1.png" alt="f-img">
              </div>
              <div class="feature-cntent">
                <h2 class="title">
                  Live Streaming
                </h2>
                <p>
                  Nulla porttitor accumsan tincidunt. Pellentesque in.
                </p>
              </div>
            </div>

          </div>
          <div class="card">
            <div class="feature-items">
              <div class="feature-thumb">
                <img src="../../assets/feature1.png" alt="f-img">
              </div>
              <div class="feature-cntent">
                <h2 class="title">
                  Live Streaming
                </h2>
                <p>
                  Nulla porttitor accumsan tincidunt. Pellentesque in.
                </p>
              </div>
            </div>

          </div>
          <div class="card ">
            <div class="feature-items ">
              <div class="feature-thumb">
                <img src="../../assets/feature1.png" alt="f-img">
              </div>
              <div class="feature-cntent">
                <h2 class="title">
                  Live Streaming
                </h2>
                <p>
                  Nulla porttitor accumsan tincidunt. Pellentesque in.
                </p>
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
  background-image: url(../../assets/Vector.png);
  background-color: rgb(16, 4, 130, 0.9);
  height: 100vh;
  color: white;
  .container{
    height: 100%;
    .row{
      display: flex;
      align-items: center;
      height: 100%;

      .col {
        width: 50%;
        h4{
          color: $green;
          padding: 10px 0;
        }
         #title{
          font-size: 2.5rem;
         }
        p{
          margin: 20px 0;
        }

      }
      .cards{
        display: flex;
        flex-wrap: wrap;
        .card{
          background-color: $blue;
          margin: 10px;
          width: 45%;
          height: 300px;
          border-radius: 5%;
          &:hover{
            background-color: $greenLight;
          }
          .feature-items{
            margin: 65px 0;
            text-align: center;
            .feature-thumb{
              width: 100px;
              height: 100px;
              border-radius: 50%;
              line-height: 150px;
              text-align: center;
              margin: 0 auto 20px;
              background: #202046;
              transition: all 0.3s;
              img{
                width: 60px;
                object-fit: contain;
              }
            }
          }
        }
      }

    }
  }
}

</style>