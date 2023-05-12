<script>
export default {
  name: 'SectionUpcoming'
}
</script>

<template>
  <div class="container-all-widht">
    <div class="container-opaco">
      <div class="container">
        <span class="subtitle">Upcoming Match</span>
        <h2 class="white">Keep Eyes & Manage upcoming Battle </h2>
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
            <div class="image-card">
              <img src="../../assets/3.png" alt="#">
              <img class="image-position" src="../../assets/3.png" alt="#">
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
                <button class="button br-rad">view more</button>
              </div>
  
  
            </div>
          </div>
          <div class="card">
            <div class="image-card">
              <img src="../../assets/2.png" alt="#">
              <img class="image-position" src="../../assets/2.png" alt="#">
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
                <button class="button br-rad">view more</button>
              </div>
  
  
            </div>
          </div>
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
                <button class="button br-rad">view more</button>
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
.container-all-widht{
  min-height: 130vh;
  background-image: url(../../assets/v-bg.png);
  position: relative;
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
  .container{
    position: absolute;
    z-index: 10;
    left: 175px;
    padding: 100px 0;
    h2{
      margin: 20px 0;
      font-size: 3rem;
      width: 50%;
    }

    .button{
    display: flex;
    padding: 20px 40px;
    margin: 20px 0;
    align-items: center;
    background-color: $greenLight;
    border: 1px solid $green;
    font-weight: bold;
    font-size: 1.1rem;

  &:hover{
    background: none;
    color: $green;
  }
}
    .cards-container{
      display: flex;
      justify-content: space-between;
      height: 100%;
      .card{
        padding: 0px;
        width: calc(100%/3.3);
        background-color: #202046;
        border-radius: 10px;
        .image-card{
          height: 300px;
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
          height: 100%;
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
          }
        
      }
    }
  }
}
}
</style>