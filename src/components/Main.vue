<script>
import LogoWrapperMain from './partials/LogoWrapperMain.vue';
import SectionAbout from './partials/SectionAbout.vue';
import SectionFeature from './partials/SectionFeature.vue';
 export default {
 name: 'Main' ,
 components:{
    LogoWrapperMain,
    SectionAbout,
    SectionFeature
}
 } 
</script>

<template>
  <LogoWrapperMain />
  <SectionAbout />
  <SectionFeature />


</template>

<style lang="scss" scoped>

</style>