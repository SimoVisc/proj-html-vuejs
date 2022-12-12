<script>
export default {
    name: "AppHero",
  }
</script>

<template>
 <div class="hero">
    <div class="text">
      <h1>Complete Your Dreams in JavaS Programming</h1>
      <p>Learn any coding program in distance and for a reasonable fee. you don't have to struggle alone, you've got our assistance and help</p>
      <button>
        <i class="fa-regular fa-arrow-down-to-bracket"></i> 
        <span>Download from E-book</span>
      </button>
    </div>
    <img src="../assets/img/hero-image.png" alt="">
  </div>     
</template>

<style lang="scss" scoped>

.hero{
   width:100%;
   display: flex;
    .text{
      width:50%;
      padding: 60px;
      p{
        padding:20px 0;
      }
    }
    img{
      width:50%;
      padding:30px;
    }
    button{
     padding: 10px 20px;
     color:#fff;
    }
}
</style>