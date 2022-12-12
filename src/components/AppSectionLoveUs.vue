<script>
import AppTestimonial from './AppTestimonial.vue';
export default {
  name: 'AppSectionLoveUs',
  components:{
    AppTestimonial
  }
}
</script>

<template>
  <div class="bg-color">
 <section class="container">
    <div class="title">
      <small>PEOPLE ARE PRAISING MAXCOACH</small>
      <h1>What make they <span class="green-color">love us?</span></h1>
    </div>
    <div class="testimonials">
      <AppTestimonial/>
    </div>
    <div class="points-container">
      <i class="fa-solid fa-period"></i>
    </div>
  </section>
 </div>
</template>
  
  <style lang="scss" scoped >
  .bg-color{
    background-color: var(--bg-primary-color);
   .title{
    width:100%;
    text-align: center;
    padding: 20px 0;
   }
   .testimonials{
    width:100%;
    display:flex;
    padding:30px 20px;

  .points-container{
    display: block;
    color: var(--primary-color);
    display: flex;
  }
    
  }
}  
  
  </style>