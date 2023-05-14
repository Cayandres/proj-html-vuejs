
<script>
export default {
  name:'cardFeature',
  props:{
    image: String,
    title: String,
    description: String,
  }
  
}
</script>

<template>
 <div class="card active ">
   <div class="feature-items">
     <div class="feature-thumb">
       <img :src="image" :alt="title">
     </div>
     <div class="feature-cntent">
       <h2 class="title">
        {{ title }}
       </h2>
       <p>
       {{ description }}
      </p>
    </div>
  </div>
  
</div>
</template>

<style lang="scss" scoped>
@use '../../../scss/partials/vars.scss' as*;
        .card{
          background-color: $blue;
          margin: 10px;
          width: 45%;
          height: 300px;
          border-radius: 5%;
          &:hover{
            background-color: $greenLight;
          }

          .feature-items{
            margin: 65px 0;
            text-align: center;
            .feature-thumb{
              width: 100px;
              height: 100px;
              border-radius: 50%;
              line-height: 150px;
              text-align: center;
              margin: 0 auto 20px;
              background: #202046;
              transition: all 0.3s;
              img{
                width: 60px;
                object-fit: contain;
              }
            }
          }
        }

</style>