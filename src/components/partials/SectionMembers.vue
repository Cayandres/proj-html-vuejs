<script>
export default {
  name: 'SectionMembers'
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
            <img src="../../assets/team1.png" alt="#">
            <ul class="opacity">
              <li><img src="../../assets/image (5).svg" alt=""><a href=""></a></li>
              <li><img src="../../assets/image (6).svg" alt=""><a href=""></a></li>
              <li><img src="../../assets/image (7).svg" alt=""><a href=""></a></li>
              <li><img src="../../assets/image (8).svg" alt=""><a href=""></a></li>
            </ul>
          </div>
          <div class="info">
            <h4>Cristiano Rolando</h4>
            <span>Ceo/Founder</span>
          </div>
        </div>

      </div>
    </div>
  </div>
</template>


<style lang="scss" scoped>
.container-all-widht{
  height: 100vh;
  background-color: green;
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
        background-color: blue;
        text-align: center;
        width: calc(100%/4.3);
        &:hover .image .opacity{
            opacity: 1;
          }
        .image{
          position: relative;
          .opacity{
            display: flex;
            position: absolute;
            right: 22px;
            bottom: 14px;
            opacity: 0;
           
            li{
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
        img{
          width: 100%;
        }
        .info{
          h4{
            padding: 10px 0;
          }
          span{
            display: block;
            padding-bottom: 10px;
          }
        }
      }

    }
  }
}
</style>