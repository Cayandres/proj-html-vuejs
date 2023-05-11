<script>
import LogoWrapperMain from './partials/LogoWrapperMain.vue';
import SectionAbout from './partials/SectionAbout.vue';
import SectionFeature from './partials/SectionFeature.vue';
import SectionLive from './partials/SectionLive.vue';
 export default {
 name: 'Main' ,
 components:{
    LogoWrapperMain,
    SectionAbout,
    SectionFeature,
    SectionLive
}
 } 
</script>

<template>
  <LogoWrapperMain />
  <SectionAbout />
  <SectionFeature />
  <SectionLive/>
  

</template>

<style lang="scss" scoped>

</style>