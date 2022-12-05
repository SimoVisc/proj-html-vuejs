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
  <div class="container">
    <AppLogo/>
    <div class="nav-bar">
      <ul>
        <li>Home <i class="fa-solid fa-chevron-down"></i> </li>
        <li>Pages <i class="fa-solid fa-chevron-down"></i> </li>
        <li>Courses <i class="fa-solid fa-chevron-down"></i> </li>
        <li>Features <i class="fa-solid fa-chevron-down"></i> </li>
        <li>Blog <i class="fa-solid fa-chevron-down"></i> </li>
        <li> Shop <i class="fa-solid fa-chevron-down"> <i class="fa-solid fa-cart-shopping"></i></i> </li>
        <li><i class="fa-solid fa-circle-user"></i></li>
      </ul>
   </div>
   <div class="search-bar">
     <input type="text" placeholder="Search...">
     <button><i class="fa-solid fa-magnifying-glass"></i></button>
   </div>
 

  </div>
</template>

<style lang="scss" >
.container{
  
  display:flex;
  justify-content: space-between;
  align-items:center;
  ul{
    display:flex;

    li{
      list-style: none;
      padding-left:10px;

      i{
        font-size: 10px;
      }
    }
  }
  .search-bar{
    text-align: end;
    input{
      border:none;
      padding:5px;
      width:40%
    }
    button{
      color: #20ad96;
      background-color: #fff;
      border:none;
      padding:5px;
    }
  }
}
</style>
