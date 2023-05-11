
<script>
export default {
  name:'SectionMatch'
}
</script>

<template>
  <div class="container-all-width">
    <div class="container">
      <div class="subtitle"><span>Trending Battle</span></div>
      <h2>Upcoming Match</h2>
      <div>
        <ul>
          <li class="active">All</li>
          <li>Pubg</li>
          <li>COD</li>
          <li>AC</li>
          <li>MCX</li>
        </ul>
      </div>
        <div class="matches-box">
          <div class="col match">
            <div class="card">
              <div class="image-card">
                <img src="../../assets/1.png" alt="#">
              </div>
              <div class="description">
                <span>xiao</span>
                <h3>ciaos</h3>
              </div>
            </div>
            <span class="vs">vs</span>
            <div class="card">
              <div class="image-card">
                <img src="../../assets/2.png" alt="#">
              </div>
              <div class="description">
                <span>xiao</span>
                <h3>ciaos</h3>
              </div>
              
            </div>

          </div>
          <div class="col info">
            <div class="description-box">
              <h2>PUBG Battleground</h2>
              <p>Queste due squadre si affronterrano in un epico battle royale dove solo una potra uscirne vittoriosa, Team Ninja o Team Wicht? Chi vincerà?</p>

            </div>
            <div class="square-info">
              <span>  10:45 </span>
              <span>10 ottobre, 2032</span>
              <div class="socials">
                <img src="../../assets/image (13).svg" alt="">
                <img src="../../assets/image (14).svg" alt="">
              </div>

            </div>
          </div>
        </div>
    </div>
  </div>
</template>

<style lang="scss" scoped>
@use '../../scss/partials/vars.scss' as*;
.container-all-width{
  background-color: $blueDark;
  min-height: 100vh;
  .container{
    padding: 100px 0;
    color: white;
    text-align: center;
    .subtitle{
      color: green;
      font-weight: bold;
    }
    h2{
      font-size: 3rem;
      padding: 20px 0;
    }
    ul{
      display: flex;
      justify-content: center;
      padding: 10px;
      li{
        padding: 10px;
      }
    }
    .matches-box{
      display: flex;
      background-color: rgb(169, 17, 17);
      width: 100%;
      border-radius: 10px;
      margin-top: 30px;
        .match{
          display: flex;
          justify-content: space-between;
          align-content: center;
          width: 50%;
          .card{
            margin: 20px;
            background-color: blue;
            border-radius: 10px;
            overflow: hidden;
            .image-card{
              width: 190px;
              padding: 15px 30px;
              background-color: black;
            }

            .description{
              text-align: left;
              margin: 10px;
              span{
                padding: 5px 0;
                display: block;
                color: green;
                font-weight: bold;
                font-size: 1rem;
              }
              h3{
                font-size: 2rem;
              }

            }
          }
          .vs{
            align-self: center;
            background-color: blue;
            padding: 35px;
            margin: 10px;
            border-radius: 10px;
            font-weight: bold;
            font-size: 1.5rem;
          }
        }
        .info{
          display: flex;
          align-items: center;
          text-align: left;
          .description-box{
            width: 70%;
            h2{
              font-size: 2rem;
              padding: 10px 0;
            }
          }

          .square-info{
            width: 30%;
            display: flex;
            flex-direction: column;
            background-color: green;
            padding: 15px 10px;
            margin: 20px;
            text-align: center;
            border-radius: 10px;
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
                background-color: blue;
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
</style>