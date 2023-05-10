
<script>
export default {
  name:'Jumbotron'
}
</script>

<template>
  <div class="container-all-width">
    <div class="container">
      <div class="row">
        <div class="col socials">
          <ul>
            <li><a href="#"><img src="../assets/img/image (4).svg" alt="ciao"></a></li>
            <li><a href="#"><img src="../assets/img/image (5).svg" alt="ciao"></a></li>
            <li><a href="#"><img src="../assets/img/image (6).svg" alt="ciao"></a></li>
            <li><a href="#"><img src="../assets/img/image (7).svg" alt="ciao"></a></li>
          </ul>      
        </div>
        <div class="col title">
          <div><span>WELCOME TO RAXG</span></div>
          <h1>ARE YOU READY FOR YOUR NEXT CHALLENGE?</h1>
          <div class="buttons">
            <button>Read More</button>
            <button>Play</button>
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
  display: flex;
  justify-content: center;
  align-items: center;
  color: white;
  background-image: url(../assets/img/banner1.png);
  object-fit: cover;
  height: 100vh;

  .container{
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
          a{
            img{
              height: 15px;
            }
          }
        }
      }
      .title{
        width: 1200px;
        margin: 0 auto;
        text-align: center;
        h1{
          font-size: 4.5rem;
          padding: 20px 0;
        }
        .buttons{
          color: green;

        }
      }
    }

  }
}

</style>