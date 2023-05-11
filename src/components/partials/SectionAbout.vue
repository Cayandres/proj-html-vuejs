<script>
export default {
  name:'SectionAbout'
}
</script>

<template>
  <div class="container-all-width">
    <div class="container">
      <div class="row">
        <div class="col image-position">

          <div class="about-thumb">
             <div class="dots-about">
               <img src="../../assets/exprience-shape.png" alt="about-dots">
             </div>
             <div class="bigsmall">
               <img src="../../assets/shape1.png" alt="bigaboutimg">
             </div>
             <div class="main-immage">
               <img  src="../../assets/exprince.jpg" alt="a-img">
             </div>
             <div class="small-thumb">
                 <img src="../../assets/shape2.png" alt="small-img">
             </div>
          </div>
                
        </div>
        <div class="col">
          <h4>12 Year Experience </h4>
          <h2>We Are The Best Gaming Company </h2>
          <p>Nulla quis lorem ut libero malesuada feugiat. Vivamus magna justo, lacinia eget consectetur sed, convallis at tellus. Cras ultricies ligula sed magna dictum porta.Praesent sapien massa, convallis a pellentesque nec, egestas non nisi praesent sapien massa ligula sed magna dictum porta. </p>
          <p>Nulla quis lorem ut libero malesuada feugiat. Vivamus magna justo, lacinia eget consectetur sed, convallis at tellus. Cras ultricies ligulaa. </p>
          <ul>
            <li><img src="../../assets/image (10).svg" alt="">Sed porttitor lectus nibh. Proin eget tortor risus. </li>
            <li><img src="../../assets/image (10).svg" alt="">Sed porttitor lectus nibh. Proin eget tortor risus. </li>
            <li><img src="../../assets/image (10).svg" alt="">Sed porttitor lectus nibh. Proin eget tortor risus. </li>
            <li><img src="../../assets/image (10).svg" alt="">Sed porttitor lectus nibh. Proin eget tortor risus. </li>
          </ul>
          <div>
            <button>discovery more</button>
            <button>play</button>
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
  min-height: 100vh;
  background-color: $blueDarkPlus;
  .container{
    padding: 210px 0 120px 0;
    .row{
      display: flex;
      img{
        width: 100%;
      }
    }
    .col{
      width: 50%;
      .about-thumb{
        margin-top: 60px;
        position: relative;
        width: 600px;
        .dots-about{
          position: absolute;
          width: 110px;
          top: -16px;
          left: -43px;
          z-index: 3;
        }
        .bigsmall{
          width: 467px;
          left: 26px;
          position: absolute;
          top: -46px;
        }
        .small-thumb{
          position: absolute;
          width: 232px;
          height: 10px;
          left: 327px;
          bottom: 188px;
        }
        .main-immage{
          height: 450px;
          width: 450px;
          img{
            height: 100%;
            position: absolute;
            z-index: 10;
            object-fit: contain;
          }
        }
      }

    }
    .col{
      width: 50%;
      color: $white;
      h4{
        color: $green;
        padding-bottom: 10px;
      }
      h2{
        font-size: 3rem;
        font-weight: 700;
        padding-bottom: 10px;
      }

      p{
        padding: 5px 0;
        line-height: 25px;
      }

      ul{
        margin: 10px 0;
        li{
          padding: 8px 0;
          display: flex;
          align-items: center;
          img{
            color: $green;
            margin-right: 10px;
            width: 30px;
            height: 30px;
            line-height: 0px;
            border-radius: 50%;
            text-align: center;
            border: 1px solid $green;
            padding: 5px;
            font-size: 14px;
          }
        }
      }
    }
  }
}
</style>