<script>
import AppLogo from './AppLogo.vue';
import AppHero from './AppHero.vue';

export default {
    name: "AppHeader",
    components: {
      AppLogo,
      AppHero
    },
  }
</script>

<template>
  <header>
  <div class="container">
    <div class="header-top">
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
    <AppHero/>  
  </div>
  </header>
</template>

<style lang="scss" scoped >
header{
  background-image: url(../assets/img/jumbo-overlay.svg);
  background-color: #e9e6e3;
  padding:20px;
  .header-top{
   display:flex;
   justify-content: space-between;
   color: var(--secondary-font-color);
  .bars{
    display:flex;
    align-items:center;
    width:70%;
  }
  ul{
    width:100%;
    display:flex;
    padding-right: 20px;

    li{
      list-style: none;
      padding-left:14px;
      cursor: pointer;

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
   background-color: #fff;
   display: flex;
   justify-content: center;
   width:15%;
   border-radius: 5px;
   padding: 10px 5px;

    input{
      background: rgba(0,0,0,0);
      border:none;
      width:60%;
    }

    button{
      color: var(--primary-color);
      background-color: #fff;
      border:none;
     
    }
  }
}
}
</style>
