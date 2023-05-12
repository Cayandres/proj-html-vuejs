<script>
export default {
  name: 'SectionShop'
}
</script>

<template>
  <div class="container-all-widht">
    <div class="container-opaco">
      <div class="container">
        <div class="title">
          <span class="subtitle">Gamer Shop</span>
          <h2 class="white">Explore Our Shop</h2>
          <div class="buttons">
          <button class="arrow-right"><a class="" href="#">
            <svg class="svg-inline--fa fa-arrow-left-long" aria-hidden="true" focusable="false" data-prefix="fas" data-icon="arrow-left-long" role="img" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 512 512" data-fa-i2svg=""><path fill="currentColor" d="M9.375 233.4l128-128c12.5-12.5 32.75-12.5 45.25 0s12.5 32.75 0 45.25L109.3 224H480c17.69 0 32 14.31 32 32s-14.31 32-32 32H109.3l73.38 73.38c12.5 12.5 12.5 32.75 0 45.25c-12.49 12.49-32.74 12.51-45.25 0l-128-128C-3.125 266.1-3.125 245.9 9.375 233.4z"></path></svg></a> 
          </button>
        <button class="active white"><a class="" href="#">
          <svg class="svg-inline--fa fa-arrow-right-long white" aria-hidden="true" focusable="false" data-prefix="fas" data-icon="arrow-right-long" role="img" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 512 512" data-fa-i2svg=""><path fill="currentColor" d="M502.6 278.6l-128 128c-12.51 12.51-32.76 12.49-45.25 0c-12.5-12.5-12.5-32.75 0-45.25L402.8 288H32C14.31 288 0 273.7 0 255.1S14.31 224 32 224h370.8l-73.38-73.38c-12.5-12.5-12.5-32.75 0-45.25s32.75-12.5 45.25 0l128 128C515.1 245.9 515.1 266.1 502.6 278.6z"></path></svg></a> 
        </button>
      </div>
        </div>
        <div class="cards-container">
  
          <div class="card">
            <div class="image">
              <img src="../../assets/s3.png" alt="#">
              <ul class="opacity">
                <li><svg class="svg-inline--fa fa-eye" aria-hidden="true" focusable="false" data-prefix="fas" data-icon="eye" role="img" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 576 512" data-fa-i2svg=""><path fill="currentColor" d="M279.6 160.4C282.4 160.1 285.2 160 288 160C341 160 384 202.1 384 256C384 309 341 352 288 352C234.1 352 192 309 192 256C192 253.2 192.1 250.4 192.4 247.6C201.7 252.1 212.5 256 224 256C259.3 256 288 227.3 288 192C288 180.5 284.1 169.7 279.6 160.4zM480.6 112.6C527.4 156 558.7 207.1 573.5 243.7C576.8 251.6 576.8 260.4 573.5 268.3C558.7 304 527.4 355.1 480.6 399.4C433.5 443.2 368.8 480 288 480C207.2 480 142.5 443.2 95.42 399.4C48.62 355.1 17.34 304 2.461 268.3C-.8205 260.4-.8205 251.6 2.461 243.7C17.34 207.1 48.62 156 95.42 112.6C142.5 68.84 207.2 32 288 32C368.8 32 433.5 68.84 480.6 112.6V112.6zM288 112C208.5 112 144 176.5 144 256C144 335.5 208.5 400 288 400C367.5 400 432 335.5 432 256C432 176.5 367.5 112 288 112z"></path></svg></li>
                <li><svg class="svg-inline--fa fa-cart-flatbed" aria-hidden="true" focusable="false" data-prefix="fas" data-icon="cart-flatbed" role="img" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 640 512" data-fa-i2svg=""><path fill="currentColor" d="M240 320h320c26.4 0 48-21.6 48-48v-192C608 53.6 586.4 32 560 32H448v128l-48-32L352 160V32H240C213.6 32 192 53.6 192 80v192C192 298.4 213.6 320 240 320zM608 384H128V64c0-35.2-28.8-64-64-64H31.1C14.4 0 0 14.4 0 32S14.4 64 31.1 64H48C56.84 64 64 71.16 64 80v335.1c0 17.6 14.4 32 32 32l66.92-.0009C161.1 453 160 458.4 160 464C160 490.5 181.5 512 208 512S256 490.5 256 464c0-5.641-1.13-10.97-2.917-16h197.9c-1.787 5.027-2.928 10.36-2.928 16C448 490.5 469.5 512 496 512c26.51 0 48.01-21.49 48.01-47.1c0-5.641-1.12-10.97-2.907-16l66.88 .0009C625.6 448 640 433.6 640 415.1C640 398.4 625.6 384 608 384z"></path></svg></li>
                <li><svg class="svg-inline--fa fa-heart" aria-hidden="true" focusable="false" data-prefix="fas" data-icon="heart" role="img" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 512 512" data-fa-i2svg=""><path fill="currentColor" d="M0 190.9V185.1C0 115.2 50.52 55.58 119.4 44.1C164.1 36.51 211.4 51.37 244 84.02L256 96L267.1 84.02C300.6 51.37 347 36.51 392.6 44.1C461.5 55.58 512 115.2 512 185.1V190.9C512 232.4 494.8 272.1 464.4 300.4L283.7 469.1C276.2 476.1 266.3 480 256 480C245.7 480 235.8 476.1 228.3 469.1L47.59 300.4C17.23 272.1 .0003 232.4 .0003 190.9L0 190.9z"></path></svg></li>
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
                <span class="price1">$199.00</span>
                <span class="price2">$199.00</span>
              </div>
            </div>
          </div>

          <div class="card">
            <div class="image">
              <img src="../../assets/s1.png" alt="#">
              <ul class="opacity">
                <li><svg class="svg-inline--fa fa-eye" aria-hidden="true" focusable="false" data-prefix="fas" data-icon="eye" role="img" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 576 512" data-fa-i2svg=""><path fill="currentColor" d="M279.6 160.4C282.4 160.1 285.2 160 288 160C341 160 384 202.1 384 256C384 309 341 352 288 352C234.1 352 192 309 192 256C192 253.2 192.1 250.4 192.4 247.6C201.7 252.1 212.5 256 224 256C259.3 256 288 227.3 288 192C288 180.5 284.1 169.7 279.6 160.4zM480.6 112.6C527.4 156 558.7 207.1 573.5 243.7C576.8 251.6 576.8 260.4 573.5 268.3C558.7 304 527.4 355.1 480.6 399.4C433.5 443.2 368.8 480 288 480C207.2 480 142.5 443.2 95.42 399.4C48.62 355.1 17.34 304 2.461 268.3C-.8205 260.4-.8205 251.6 2.461 243.7C17.34 207.1 48.62 156 95.42 112.6C142.5 68.84 207.2 32 288 32C368.8 32 433.5 68.84 480.6 112.6V112.6zM288 112C208.5 112 144 176.5 144 256C144 335.5 208.5 400 288 400C367.5 400 432 335.5 432 256C432 176.5 367.5 112 288 112z"></path></svg></li>
                <li><svg class="svg-inline--fa fa-cart-flatbed" aria-hidden="true" focusable="false" data-prefix="fas" data-icon="cart-flatbed" role="img" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 640 512" data-fa-i2svg=""><path fill="currentColor" d="M240 320h320c26.4 0 48-21.6 48-48v-192C608 53.6 586.4 32 560 32H448v128l-48-32L352 160V32H240C213.6 32 192 53.6 192 80v192C192 298.4 213.6 320 240 320zM608 384H128V64c0-35.2-28.8-64-64-64H31.1C14.4 0 0 14.4 0 32S14.4 64 31.1 64H48C56.84 64 64 71.16 64 80v335.1c0 17.6 14.4 32 32 32l66.92-.0009C161.1 453 160 458.4 160 464C160 490.5 181.5 512 208 512S256 490.5 256 464c0-5.641-1.13-10.97-2.917-16h197.9c-1.787 5.027-2.928 10.36-2.928 16C448 490.5 469.5 512 496 512c26.51 0 48.01-21.49 48.01-47.1c0-5.641-1.12-10.97-2.907-16l66.88 .0009C625.6 448 640 433.6 640 415.1C640 398.4 625.6 384 608 384z"></path></svg></li>
                <li><svg class="svg-inline--fa fa-heart" aria-hidden="true" focusable="false" data-prefix="fas" data-icon="heart" role="img" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 512 512" data-fa-i2svg=""><path fill="currentColor" d="M0 190.9V185.1C0 115.2 50.52 55.58 119.4 44.1C164.1 36.51 211.4 51.37 244 84.02L256 96L267.1 84.02C300.6 51.37 347 36.51 392.6 44.1C461.5 55.58 512 115.2 512 185.1V190.9C512 232.4 494.8 272.1 464.4 300.4L283.7 469.1C276.2 476.1 266.3 480 256 480C245.7 480 235.8 476.1 228.3 469.1L47.59 300.4C17.23 272.1 .0003 232.4 .0003 190.9L0 190.9z"></path></svg></li>
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
                <span class="price1">$199.00</span>
                <span class="price2">$199.00</span>
              </div>
            </div>
          </div>

          <div class="card">
            <div class="image">
              <img src="../../assets/s2.png" alt="#">
              <ul class="opacity">
                <li><svg class="svg-inline--fa fa-eye" aria-hidden="true" focusable="false" data-prefix="fas" data-icon="eye" role="img" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 576 512" data-fa-i2svg=""><path fill="currentColor" d="M279.6 160.4C282.4 160.1 285.2 160 288 160C341 160 384 202.1 384 256C384 309 341 352 288 352C234.1 352 192 309 192 256C192 253.2 192.1 250.4 192.4 247.6C201.7 252.1 212.5 256 224 256C259.3 256 288 227.3 288 192C288 180.5 284.1 169.7 279.6 160.4zM480.6 112.6C527.4 156 558.7 207.1 573.5 243.7C576.8 251.6 576.8 260.4 573.5 268.3C558.7 304 527.4 355.1 480.6 399.4C433.5 443.2 368.8 480 288 480C207.2 480 142.5 443.2 95.42 399.4C48.62 355.1 17.34 304 2.461 268.3C-.8205 260.4-.8205 251.6 2.461 243.7C17.34 207.1 48.62 156 95.42 112.6C142.5 68.84 207.2 32 288 32C368.8 32 433.5 68.84 480.6 112.6V112.6zM288 112C208.5 112 144 176.5 144 256C144 335.5 208.5 400 288 400C367.5 400 432 335.5 432 256C432 176.5 367.5 112 288 112z"></path></svg></li>
                <li><svg class="svg-inline--fa fa-cart-flatbed" aria-hidden="true" focusable="false" data-prefix="fas" data-icon="cart-flatbed" role="img" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 640 512" data-fa-i2svg=""><path fill="currentColor" d="M240 320h320c26.4 0 48-21.6 48-48v-192C608 53.6 586.4 32 560 32H448v128l-48-32L352 160V32H240C213.6 32 192 53.6 192 80v192C192 298.4 213.6 320 240 320zM608 384H128V64c0-35.2-28.8-64-64-64H31.1C14.4 0 0 14.4 0 32S14.4 64 31.1 64H48C56.84 64 64 71.16 64 80v335.1c0 17.6 14.4 32 32 32l66.92-.0009C161.1 453 160 458.4 160 464C160 490.5 181.5 512 208 512S256 490.5 256 464c0-5.641-1.13-10.97-2.917-16h197.9c-1.787 5.027-2.928 10.36-2.928 16C448 490.5 469.5 512 496 512c26.51 0 48.01-21.49 48.01-47.1c0-5.641-1.12-10.97-2.907-16l66.88 .0009C625.6 448 640 433.6 640 415.1C640 398.4 625.6 384 608 384z"></path></svg></li>
                <li><svg class="svg-inline--fa fa-heart" aria-hidden="true" focusable="false" data-prefix="fas" data-icon="heart" role="img" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 512 512" data-fa-i2svg=""><path fill="currentColor" d="M0 190.9V185.1C0 115.2 50.52 55.58 119.4 44.1C164.1 36.51 211.4 51.37 244 84.02L256 96L267.1 84.02C300.6 51.37 347 36.51 392.6 44.1C461.5 55.58 512 115.2 512 185.1V190.9C512 232.4 494.8 272.1 464.4 300.4L283.7 469.1C276.2 476.1 266.3 480 256 480C245.7 480 235.8 476.1 228.3 469.1L47.59 300.4C17.23 272.1 .0003 232.4 .0003 190.9L0 190.9z"></path></svg></li>
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
                <span class="price1">$199.00</span>
                <span class="price2">$199.00</span>
              </div>
            </div>
          </div>

          <div class="card">
            <div class="image">
              <img src="../../assets/s4.png" alt="#">
              <ul class="opacity">
                <li><svg class="svg-inline--fa fa-eye" aria-hidden="true" focusable="false" data-prefix="fas" data-icon="eye" role="img" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 576 512" data-fa-i2svg=""><path fill="currentColor" d="M279.6 160.4C282.4 160.1 285.2 160 288 160C341 160 384 202.1 384 256C384 309 341 352 288 352C234.1 352 192 309 192 256C192 253.2 192.1 250.4 192.4 247.6C201.7 252.1 212.5 256 224 256C259.3 256 288 227.3 288 192C288 180.5 284.1 169.7 279.6 160.4zM480.6 112.6C527.4 156 558.7 207.1 573.5 243.7C576.8 251.6 576.8 260.4 573.5 268.3C558.7 304 527.4 355.1 480.6 399.4C433.5 443.2 368.8 480 288 480C207.2 480 142.5 443.2 95.42 399.4C48.62 355.1 17.34 304 2.461 268.3C-.8205 260.4-.8205 251.6 2.461 243.7C17.34 207.1 48.62 156 95.42 112.6C142.5 68.84 207.2 32 288 32C368.8 32 433.5 68.84 480.6 112.6V112.6zM288 112C208.5 112 144 176.5 144 256C144 335.5 208.5 400 288 400C367.5 400 432 335.5 432 256C432 176.5 367.5 112 288 112z"></path></svg></li>
                <li><svg class="svg-inline--fa fa-cart-flatbed" aria-hidden="true" focusable="false" data-prefix="fas" data-icon="cart-flatbed" role="img" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 640 512" data-fa-i2svg=""><path fill="currentColor" d="M240 320h320c26.4 0 48-21.6 48-48v-192C608 53.6 586.4 32 560 32H448v128l-48-32L352 160V32H240C213.6 32 192 53.6 192 80v192C192 298.4 213.6 320 240 320zM608 384H128V64c0-35.2-28.8-64-64-64H31.1C14.4 0 0 14.4 0 32S14.4 64 31.1 64H48C56.84 64 64 71.16 64 80v335.1c0 17.6 14.4 32 32 32l66.92-.0009C161.1 453 160 458.4 160 464C160 490.5 181.5 512 208 512S256 490.5 256 464c0-5.641-1.13-10.97-2.917-16h197.9c-1.787 5.027-2.928 10.36-2.928 16C448 490.5 469.5 512 496 512c26.51 0 48.01-21.49 48.01-47.1c0-5.641-1.12-10.97-2.907-16l66.88 .0009C625.6 448 640 433.6 640 415.1C640 398.4 625.6 384 608 384z"></path></svg></li>
                <li><svg class="svg-inline--fa fa-heart" aria-hidden="true" focusable="false" data-prefix="fas" data-icon="heart" role="img" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 512 512" data-fa-i2svg=""><path fill="currentColor" d="M0 190.9V185.1C0 115.2 50.52 55.58 119.4 44.1C164.1 36.51 211.4 51.37 244 84.02L256 96L267.1 84.02C300.6 51.37 347 36.51 392.6 44.1C461.5 55.58 512 115.2 512 185.1V190.9C512 232.4 494.8 272.1 464.4 300.4L283.7 469.1C276.2 476.1 266.3 480 256 480C245.7 480 235.8 476.1 228.3 469.1L47.59 300.4C17.23 272.1 .0003 232.4 .0003 190.9L0 190.9z"></path></svg></li>
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
                <span class="price1">$199.00</span>
                <span class="price2">$199.00</span>
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
  height: 100vh;
  background-image: url(../../assets/shop-bg.png);
  position: relative;
    .buttons{
    position: absolute;
    right: 0px;
    top: 142px;
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
  .container-opaco{
    &::after{
    position: absolute;
    content: "";
    top: 0;
    left: 0;
    right: 0;
    bottom: 0;
    width: 100%;
    background: rgba(26, 25, 53, 0.8);
  }
}
  .container{
    position: absolute;
    z-index: 10;
    left: 175px;
    padding: 100px 0;
    height: 2px;
    .title{
      text-align: center;
      width: 39%;
      h2{
        font-size: 3rem;
        padding: 20px 0;
      }
    }
    .cards-container{
      display: flex;
      justify-content: space-between;
      .card{
        text-align: left;
        width: calc(100%/4.3);
        color: white;
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
          background-color: $blueDark;
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
              background-color: $blue;
              &:hover{
                background-color: $green;
              }
              svg{
                height: 20px;
                color: white;
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
            font-size: 1.2rem;
            padding-bottom: 10px;
          }
          span{
            padding: 10px 10px 0 0;
          }
          .price1{
            color: $green;

          }
        }
      }

    }
  }
}
</style>