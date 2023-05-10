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
          <span>cerca</span>
          <span>carrello</span>

        </div>
      </div>
    </div>
  </div>
</template>

<style lang="scss" scoped>
@use '../../scss/main.scss' as*;
.container-all-width{
  position: fixed;
  z-index: 999;
  width: 100%;
  .container{
    margin: 0 auto;
    height: 80px;

    .row{
      color: white;
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
        span{
          padding: 10px;
        }
      }
    }
  }
}

</style>