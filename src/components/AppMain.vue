<script>
import AppSectionToday from './AppSectionToday.vue';
import AppSectionStunning from './AppSectionStunning.vue';
import AppSectionCourses from './AppSectionCourses.vue';
import AppSectionPace from './AppSectionPace.vue';
import AppSectionMobile from './AppSectionMobile.vue';
import AppSectionEvents from './AppSectionEvents.vue';
import AppSectionLoveUs from './AppSectionLoveUs.vue';
import AppSectionOnlineCertification from './AppSectionOnlineCertification.vue'

export default {
  name: 'AppMain',
  components:{
    AppSectionToday,
    AppSectionStunning,
    AppSectionCourses,
    AppSectionPace,
    AppSectionMobile,
    AppSectionEvents,
    AppSectionLoveUs,
    AppSectionOnlineCertification
}
}
</script>

<template>
  <main>
    <AppSectionToday/>
    <AppSectionStunning/>
    <AppSectionCourses/>
    <AppSectionPace/>
    <AppSectionMobile/>
    <AppSectionEvents/>
    <AppSectionLoveUs/>
    <AppSectionOnlineCertification/>
</main>
</template>

<style lang="scss">

</style>
