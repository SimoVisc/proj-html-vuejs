<script>

import AppHeader from './components/AppHeader.vue';
import AppMain from './components/AppMain.vue';
import AppFooter from './components/AppFooter.vue';

export default {
  components: {
    AppHeader,
    AppMain,
    AppFooter,
  },
  }
</script>

<template>
    <AppHeader/>
    <AppMain/>
    <AppFooter/>
</template>

<style lang="scss">
@import './style/global.scss';
@import url('https://fonts.googleapis.com/css2?family=Inter&family=Lato&display=swap');
</style>
