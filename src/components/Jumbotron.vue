
<script>
export default {
  name:'Jumbotron'
}
</script>

<template>
  <div class="container-all-width">
    <div class="container-opaco">
      <div class="container">
        <div class="row">
          <div class="col socials">
            <ul>
              <li ><a href="#"><img src="../assets/img/image (4).svg" alt="ciao"></a></li>
              <li class="active"><a href="#"><img src="../assets/img/image (5).svg" alt="ciao"></a></li>
              <li><a href="#"><img src="../assets/img/image (6).svg" alt="ciao"></a></li>
              <li><a href="#"><img src="../assets/img/image (7).svg" alt="ciao"></a></li>
            </ul>      
          </div>
          <div class="col title">
            <div><span class="subtitle">WELCOME TO RAXG</span></div>
            <h1>ARE YOU READY FOR YOUR NEXT CHALLENGE ?</h1>
            <div class="buttons">
              <button class="big-button br-rad">Read More<svg class="svg-inline--fa fa-arrow-right-long" aria-hidden="true" focusable="false" data-prefix="fas" data-icon="arrow-right-long" role="img" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 512 512" data-fa-i2svg=""><path fill="currentColor" d="M502.6 278.6l-128 128c-12.51 12.51-32.76 12.49-45.25 0c-12.5-12.5-12.5-32.75 0-45.25L402.8 288H32C14.31 288 0 273.7 0 255.1S14.31 224 32 224h370.8l-73.38-73.38c-12.5-12.5-12.5-32.75 0-45.25s32.75-12.5 45.25 0l128 128C515.1 245.9 515.1 266.1 502.6 278.6z"></path></svg></button>
               <a class="play" href="#">
                <svg class="svg-inline--fa fa-play" aria-hidden="true" focusable="false" data-prefix="fas" data-icon="play" role="img" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 384 512" data-fa-i2svg=""><path fill="currentColor" d="M361 215C375.3 223.8 384 239.3 384 256C384 272.7 375.3 288.2 361 296.1L73.03 472.1C58.21 482 39.66 482.4 24.52 473.9C9.377 465.4 0 449.4 0 432V80C0 62.64 9.377 46.63 24.52 38.13C39.66 29.64 58.21 29.99 73.03 39.04L361 215z"></path></svg>
               </a> 
            </div>
          </div>
        </div>
      </div>

    </div>
  </div>
  
</template>

<style lang="scss" scoped>
@use '../scss/main.scss' as*;
@use '../scss/partials/vars.scss' as*;

.container-all-width{
  position: relative;
  display: flex;
  justify-content: center;
  align-items: center;
  color: $white;
  background-image: url(../assets/img/banner1.png);
  object-fit: cover;
  height: 100vh;

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
    top: 40px;
    right: 63px;
    position: absolute;
    z-index: 10;
    padding-top: 80px;
    width: 1400px;
    .row{
      display: flex;
      justify-content: center;
      .socials{
        margin: 45px 0;
        li{
          height: 45px;
          padding: 15px;
          margin: 5px;
          background-color: $blueDark;
          border-radius: 50%;
          &:hover{
            background-color: $greenLight;
          }
          a{
            img{
              height: 15px;
              color: $greenLight;
            }
          }
        }
        .active{
          background-color: $greenLight;
        }
      }
      .title{
        width: 1200px;
        margin: 0 auto;
        text-align: center;
        h1{
          font-size: 5.5rem;
          padding: 20px 0;
        }
        .buttons{
          display: flex;
          justify-content: center;

        }
      }
    }

  }
}

</style>