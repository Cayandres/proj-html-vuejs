<script>
 export default {
 name: 'Footer' 
 }
</script>

<template>
  <div class="container-all-width">
    <div class="container">
      <div class="row">
        <div class="col logo">
          <div>
            <img src="../assets/img/menulogo.png" alt="logomenu">
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
      </div>
      <div class="row">
        <div class="col logo">
          <div>
            <span>Copyright RaxG | designed by NextGeneratorDev</span>
          </div>
        </div>
        <div class="col ">
          <ul class="icons">
            <li><img src="../assets/image (10).svg" alt=""></li>
            <li><img src="../assets/image (10).svg" alt=""></li>
            <li><img src="../assets/image (10).svg" alt=""></li>
            <li><img src="../assets/image (10).svg" alt=""></li>
          </ul>
        </div>
      </div>
    </div>
  </div>
  
</template>

<style lang="scss" scoped>
.container-all-width{
  height: 50vh;
  background-image: url(../assets/footer-bg.png);
  .container{
    padding: 120px 0;
    margin: 0 auto;
    height: 80px;
    
    .row{
      color: white;
      display: flex;
      justify-content: space-between;
      align-items: center;
      padding-bottom: 20px;
      border-bottom: 1px solid white;
      .menu ul{
        display: flex;
        li{
          list-style: none;
          padding: 0 10px;
        }
      }

    }
  }
}
</style>