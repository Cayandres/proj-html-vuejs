<script>
export default {
  name: 'SectionMembers'
}
</script>

<template>
  <div class="container-all-widht">
    <div class="container">
      <span>Testimonials</span>
      <h2>What Our Client Say </h2>
      <div class="cards-container">
        <div class="card">
          <div class="image">
            <img src="../../assets/test1.png" alt="#">
            <div class="opacity">
              <img src="../../assets/image (15).svg" alt="">
              <p>
                Donec sollicitudin molestie malesuada. Vestibulum ac diam sit amet quam vehicula
                elementum
                sed sit amet dui. Cras
                ultricies ligula sed magna dictum porta. Donec rutrum congue leo eget
              </p>
              <h4>Mohamad Salah</h4>
              <span>Ceo/Founder</span>
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
        text-align: center;
        width: calc(100%/4.3);
        
        &:hover .image .opacity{
            opacity: 1;
          }
          img{
          width: 100%;
        }
        .image{
          position: relative;
          .opacity{
            padding: 20px;
            position: absolute;
            left: 0px;
            top: 0px;
            opacity: 0;
            background-color: white;
            height: 100%;
            border-radius: 10px;
            text-align: left;
            transition: all 0.2s;
            img{
              width: 50px;
            }
            p{
              font-size: 1.2rem;
            }
            h4{
              font-size: 1.6rem;
              padding: 10px 0;
            }
          }
        }

      }

    }
  }
}
</style>