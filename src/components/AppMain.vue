<script>
import AppSection1 from './AppSection1.vue';
import AppSection2 from './AppSection2.vue';
export default {
  name: 'AppMain',
  components:{
    AppSection1,
    AppSection2
  }
}
</script>

<template>
  <main class="container">
    <AppSection1/>
    <AppSection2/>
 
</main>
</template>

<style lang="scss">

</style>
