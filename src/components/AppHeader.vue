<script>
import AppLogo from './AppLogo.vue';

export default {
    name: "AppMain",
    components: {
      AppLogo
    },
  }
</script>

<template>
  <header>
  <div class="container">
    <AppLogo/>
    <div class="bars">
      <div class="nav-bar">
        <ul>
          <li>Home <i class="fa-solid fa-chevron-down"></i> </li>
          <li>Pages <i class="fa-solid fa-chevron-down"></i> </li>
          <li>Courses <i class="fa-solid fa-chevron-down"></i> </li>
          <li>Features <i class="fa-solid fa-chevron-down"></i> </li>
          <li>Blog <i class="fa-solid fa-chevron-down"></i> </li>
          <li> Shop <i class="fa-solid fa-chevron-down"> <i class="fa-solid fa-cart-shopping big"></i></i> </li>
          <li><i class="fa-solid fa-circle-user big"></i></li>
        </ul>
     </div>
     <div class="search-bar">
       <input type="text" placeholder="Search...">
       <button><i class="fa-solid fa-magnifying-glass"></i></button>
     </div>
    </div>
  </div>
    <div class="hero container">
      <div class="text-container">
        <h1>Complete Your Dreams in JavaS Programming</h1>
        <p>Learn any coding program in distance and for a reasonable fee. you don't have to struggle alone, you've got our assistance and help</p>
        <button>Download from E-book</button>
      </div>
      <div class="img-container">
        <img src="../assets/img/home-5-hero-image.png" alt="">
      </div>
    </div>
  
</header>
</template>

<style lang="scss" >
header{
  background-image: url(../assets/img/jumbo-overlay.svg);
  background-color: #e9e6e3;
.container{
  display:flex;
  justify-content: space-between;
 
  .bars{
    display:flex;
    align-items:center;
  }
  ul{
    display:flex;
    padding-left: 10px;

    li{
      list-style: none;
      padding-left:10px;

      i{
        font-size: 10px;
      }
      .big{
        font-size: 16px;
        padding-right:5px
      }
    }
  }
  .search-bar{
  display: flex;
    justify-content: end;

    input{
      border:none;
      padding:5px;
      width:30%
    }
    
    button{
      color: #20ad96;
      background-color: #fff;
      border:none;
      padding:5px;
    }
  }
}
.hero{
  .text-container{
    width:50%;
    padding:80px;
    p{
      padding:15px 0;
    }
  }
  .img-container{
    width:50%;
   padding-right:20px;
   img{
    width:100%
   }
  }
  }
}
</style>
