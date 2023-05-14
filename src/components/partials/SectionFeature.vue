<script>
import { cardsFeature } from '../../data/menus';
import cardFeature from './sectionCards/cardFeature.vue';
export default {
  name:'SectionFeature',
  props:{
    image: String,
    title: String,
    description: String,
  },
  data(){
    return{
      cardsFeature
    }
  },
  components:{
    cardFeature
  },
  mounted(){
    console.log(this. cardsFeature);
  }
}
</script>

<template>
  <div class="container-all-width">
    <div class="container-opaco">
      <div class="container">
        <div class="row">
          <div class="col description">
            <h4>Our Extreme Feature</h4>
            <h2 id="title">The Best Gaming Arena On The World! </h2>
            <p>Nulla quis lorem ut libero malesuada feugiat. Vivamus magna justo, lacinia eget consectetur sed, at tellus. Cras ultricies ligula sed magna ivamus magna justo, dictum porta. sapien massa, convallis. </p>
          </div>
          <div class="col cards">
            <cardFeature 
              v-for="(card, index) in cardsFeature"
              :key="index"
              :image="card.image"
              :title="card.title"
              :description="card.description"
               />
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
  position: relative;
  background-image: url(../../assets/Vector.png);
  background-color: rgb(16, 4, 130, 0.9);
  height: 100vh;
  color: white;
  .container-opaco{

    &::after{
      position: absolute;
      content: "";
      top: 0;
      left: 0;
      right: 0;
      bottom: 0;
      width: 100%;
      background: rgba(26, 25, 53, 0.5);
    }
  }
  .container{
    position: absolute;
    width: 1200px;
    height: 100%;
    z-index: 10;
    left: 180px;
    
    .row{
      display: flex;
      align-items: center;
      justify-content: space-betweens;
      height: 100%;

      .col {
        width: 50%;
        h4{
          color: $green;
          padding: 10px 0;
        }
         #title{
          font-size: 3rem;
         }
        p{
          margin: 20px 0;
        }

      }
      .cards{
        
        display: flex;
        flex-wrap: wrap;

      }

    }
  }
}

</style>