<script>
export default {
  name: 'SectionShop'
}
</script>

<template>
  <div class="container-all-widht">
    <div class="container">
      <span>Team Members</span>
      <h2>Our Experts Team Members</h2>
      <div class="cards-container">

        <div class="card">
          <div class="image">
            <img src="../../assets/s3.png" alt="#">
            <ul class="opacity">
              <li><img src="../../assets/image (16).svg" alt=""></li>
              <li><img src="../../assets/image (17).svg" alt=""></li>
              <li><img src="../../assets/image (18).svg" alt=""></li>
            </ul>
          </div>
          <div class="info">
            <div>
              <ul>
                <li><img src="../../assets/image (19).svg" alt=""></li>
                <li><img src="../../assets/image (19).svg" alt=""></li>
                <li><img src="../../assets/image (20).svg" alt=""></li>
                <li><img src="../../assets/image (20).svg" alt=""></li>
              </ul>
            </div>
            <h4>Playstatio</h4>
            <div>
              <span>199</span>
              <span>199</span>
            </div>
          </div>
        </div>
        <div class="card">
          <div class="image">
            <img src="../../assets/s3.png" alt="#">
            <ul class="opacity">
              <li><img src="../../assets/image (16).svg" alt=""></li>
              <li><img src="../../assets/image (17).svg" alt=""></li>
              <li><img src="../../assets/image (18).svg" alt=""></li>
            </ul>
          </div>
          <div class="info">
            <div>
              <ul>
                <li><img src="../../assets/image (19).svg" alt=""></li>
                <li><img src="../../assets/image (19).svg" alt=""></li>
                <li><img src="../../assets/image (20).svg" alt=""></li>
                <li><img src="../../assets/image (20).svg" alt=""></li>
              </ul>
            </div>
            <h4>Playstatio</h4>
            <div>
              <span>199</span>
              <span>199</span>
            </div>
          </div>
        </div>
        <div class="card">
          <div class="image">
            <img src="../../assets/s3.png" alt="#">
            <ul class="opacity">
              <li><img src="../../assets/image (16).svg" alt=""></li>
              <li><img src="../../assets/image (17).svg" alt=""></li>
              <li><img src="../../assets/image (18).svg" alt=""></li>
            </ul>
          </div>
          <div class="info">
            <div>
              <ul>
                <li><img src="../../assets/image (19).svg" alt=""></li>
                <li><img src="../../assets/image (19).svg" alt=""></li>
                <li><img src="../../assets/image (20).svg" alt=""></li>
                <li><img src="../../assets/image (20).svg" alt=""></li>
              </ul>
            </div>
            <h4>Playstatio</h4>
            <div>
              <span>199</span>
              <span>199</span>
            </div>
          </div>
        </div>
        <div class="card">
          <div class="image">
            <img src="../../assets/s3.png" alt="#">
            <ul class="opacity">
              <li><img src="../../assets/image (16).svg" alt=""></li>
              <li><img src="../../assets/image (17).svg" alt=""></li>
              <li><img src="../../assets/image (18).svg" alt=""></li>
            </ul>
          </div>
          <div class="info">
            <div>
              <ul>
                <li><img src="../../assets/image (19).svg" alt=""></li>
                <li><img src="../../assets/image (19).svg" alt=""></li>
                <li><img src="../../assets/image (20).svg" alt=""></li>
                <li><img src="../../assets/image (20).svg" alt=""></li>
              </ul>
            </div>
            <h4>Playstatio</h4>
            <div>
              <span>199</span>
              <span>199</span>
            </div>
          </div>
        </div>

      </div>
    </div>
  </div>
</template>


<style lang="scss" scoped>
.container-all-widht{
  height: 100vh;
  background-color: rgb(134, 19, 111);
  .container{
    padding: 100px 0;
    height: 2px;
    h2{
      font-size: 3rem;
      width: 50%;
    }
    .cards-container{
      display: flex;
      justify-content: space-between;
      .card{
        text-align: left;
        width: calc(100%/4.3);
        &:hover .image .opacity{
            opacity: 1;
          }
        img{
          height: 100%;
        }
        .image{
          display: flex;
          width: 100%;
          justify-content: center;
          position: relative;
          background-color: black;
          height: 250px;
          padding: 40px;
          border-radius: 10px;
          .opacity{
            display: flex;
            position: absolute;
            right: 55px;
            bottom: 30px;
            opacity: 0;
           
            li{
              text-align: center;
              line-height: 50px;
              height: 40px;
              width: 40px;
              margin: 0 10px;
              border-radius: 50%;
              background-color: blue;
              img{
                height: 20px;
              }
            }
          }
        }
     
        .info{
          ul{
            display: flex;
            padding: 10px 0;
            li{
              margin: 0 5px;
              img{
                width: 20px;
              }
            }
          }
          h4{
            padding-bottom: 10px;
          }
          span{
            padding-bottom: 10px;
          }
        }
      }

    }
  }
}
</style>