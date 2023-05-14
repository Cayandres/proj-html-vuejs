<script>
export default {
  name: 'LogoWrapperMain'
}
</script>

<template>
  <div class="container">
    <div class="images">
      <div><img src="/img/1.png" alt=""></div>
      <div><img src="/img/2.png" alt=""></div>
      <div><img src="/img/3.png" alt=""></div>
      <div><img src="/img/4.png" alt=""></div>
      <div><img src="/img/5.png" alt=""></div>
      <div><img src="/img/6.png" alt=""></div>
    </div>
  </div>
</template>

<style lang="scss" scoped>
@use '../../scss/partials/vars.scss' as*;
.container{
  position: absolute;
  bottom: -100px;
  left: 169px;
  background-color: $blueDark;
  border-radius: 10px;
  .images{
    display: flex;
    justify-content: space-around;
    align-items: center;
    padding: 40px 10px;

    img{
      width: 95%;
    }
  }
}
</style>