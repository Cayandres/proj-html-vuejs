<script>
export default {
  name: 'Navbar'
}
</script>

<template>
  <div class="container-all-width">
    <div class="container">
      <div class="row">
        <div class="col logo">
          <div>
            <img src="../../assets/img/menulogo.png" alt="logomenu">
          </div>
        </div>
        <div class="col menu">
          <ul>
            <li>Home</li>
            <li>Pages</li>
            <li>Tournament</li>
            <li>Shop</li>
            <li>Blog</li>
            <li>Conctact</li>
          </ul>
        </div>
        <div class="col button">
          <div><svg class="svg-inline--fa fa-magnifying-glass" aria-hidden="true" focusable="false" data-prefix="fas" data-icon="magnifying-glass" role="img" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 512 512" data-fa-i2svg=""><path fill="currentColor" d="M500.3 443.7l-119.7-119.7c27.22-40.41 40.65-90.9 33.46-144.7C401.8 87.79 326.8 13.32 235.2 1.723C99.01-15.51-15.51 99.01 1.724 235.2c11.6 91.64 86.08 166.7 177.6 178.9c53.8 7.189 104.3-6.236 144.7-33.46l119.7 119.7c15.62 15.62 40.95 15.62 56.57 0C515.9 484.7 515.9 459.3 500.3 443.7zM79.1 208c0-70.58 57.42-128 128-128s128 57.42 128 128c0 70.58-57.42 128-128 128S79.1 278.6 79.1 208z"></path></svg></div>
          <div><svg class="svg-inline--fa fa-bag-shopping" aria-hidden="true" focusable="false" data-prefix="fas" data-icon="bag-shopping" role="img" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 448 512" data-fa-i2svg=""><path fill="currentColor" d="M112 112C112 50.14 162.1 0 224 0C285.9 0 336 50.14 336 112V160H400C426.5 160 448 181.5 448 208V416C448 469 405 512 352 512H96C42.98 512 0 469 0 416V208C0 181.5 21.49 160 48 160H112V112zM160 160H288V112C288 76.65 259.3 48 224 48C188.7 48 160 76.65 160 112V160zM136 256C149.3 256 160 245.3 160 232C160 218.7 149.3 208 136 208C122.7 208 112 218.7 112 232C112 245.3 122.7 256 136 256zM312 208C298.7 208 288 218.7 288 232C288 245.3 298.7 256 312 256C325.3 256 336 245.3 336 232C336 218.7 325.3 208 312 208z"></path></svg></div>
          <span class="number">0</span>
        </div>
      </div>
    </div>
  </div>
</template>

<style lang="scss" scoped>
@use '../../scss/main.scss' as*;
@use '../../scss/partials/vars.scss' as*;
.container-all-width{
  position: fixed;
  z-index: 999;
  width: 100%;
  .container{
    margin: 0 auto;
    height: 80px;

    .row{
      color: $white;
      display: flex;
      justify-content: space-between;
      align-items: center;
      .menu ul{
        display: flex;
        li{
          list-style: none;
          padding: 0 20px;
        }
      }
      .button{
        display: flex;
        position: relative;
        div{
          margin: 5px;
          padding: 10px;
          background-color: $white;
          border-radius: 50%;
          line-height: 20px;
          svg{
            color: $blue;
            height: 17px;
          }
        }
          .number{
            position: absolute;
            top: -10px;
            right: -10px;
            padding: 10px;
            background-color: $blueLight;
            border-radius: 50%;
            height: 30px;
            line-height: 10px;
          }
        }
    }
  }
}

</style>