<script>
import LogoWrapperMain from './partials/LogoWrapperMain.vue';
import SectionAbout from './partials/SectionAbout.vue';
import SectionFeature from './partials/SectionFeature.vue';
import SectionLive from './partials/SectionLive.vue';
import SectionMatch from './partials/SectionMatch.vue';
import SectionMembers from './partials/SectionMembers.vue';
import SectionNews from './partials/SectionNews.vue';
import SectionShop from './partials/SectionShop.vue';
import SectionTestimonials from './partials/SectionTestimonials.vue';
import SectionTrending from './partials/SectionTrending.vue';
import SectionUpcoming from './partials/SectionUpcoming.vue';

 export default {
 name: 'Main' ,
 components:{
    LogoWrapperMain,
    SectionAbout,
    SectionFeature,
    SectionLive,
    SectionMatch,
    SectionTrending,
    SectionUpcoming,
    SectionMembers,
    SectionTestimonials,
    SectionShop,
    SectionNews,
}
 } 
</script>

<template>
  <LogoWrapperMain />
  <SectionAbout />
  <SectionFeature />
  <SectionLive />
  <SectionMatch />
  <sectionTrending />
  <SectionUpcoming />
  <SectionMembers />
  <SectionTestimonials />
  <SectionShop />
  <SectionNews />

</template>

<style lang="scss" scoped>

</style>