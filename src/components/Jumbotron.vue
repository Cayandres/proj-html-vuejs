
<script>
export default {
  name:'Jumbotron'
}
</script>

<template>
  <div class="container-all-width">
    <div class="container">
      <div class="row">
        <div class="col">
          <ul>
            <li>ciao</li>
            <li></li>
            <li></li>
            <li></li>
          </ul>      
        </div>
        <div class="col">
          <div><span></span></div>
          <h1></h1>
          <div>
            <button></button>
            <button></button>
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
  color: white;
  background-image: url(../assets/img/banner1.png);
  object-fit: cover;
  height: 800px;
  .container{
    padding-top: 80px;
  }
}

</style>