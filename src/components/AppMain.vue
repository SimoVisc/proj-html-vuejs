<script>
import AppSectionToday from './AppSectionToday.vue';
import AppSectionStunning from './AppSectionStunning.vue';
import AppSectionCourses from './AppSectionCourses.vue';
export default {
  name: 'AppMain',
  components:{
    AppSectionToday,
    AppSectionStunning,
    AppSectionCourses
}
}
</script>

<template>
  <main class="container">
    <AppSectionToday/>
    <AppSectionStunning/>
    <AppSectionCourses/>
 
</main>
</template>

<style lang="scss">

</style>
