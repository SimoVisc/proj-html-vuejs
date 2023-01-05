<script>
import AppLogo from './AppLogo.vue';
import AppHero from './AppHero.vue';

export default {
  name: "AppHeader",
  components: {
    AppLogo,
    AppHero
  },
  data(){
    return {
      links: [
        {
          href: "#",
          label:"Home",
          active: true
        },
        {
          href: "#",
          label:"Pages",
          active: false
        },
        {
          href: "#",
          label:"Courses",
          active: false
        },
        {
          href: "#",
          label:"Features",
          active: false
        },
        {
          href: "#",
          label:"Blog",
          active: false
        },
        {
          href: "#",
          label:"Shop",
          active: false
        }
      ]
    }
  },
  methods: {
    changeLink(index){
     this.links.forEach((elm, i) =>{
     if (i === index) {
      elm.active = true
     }else{
      elm.active = false
     }
     });
    }
  }
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
            <li v-for=" (link, index) in links"><a :class=" {active : link.active} " :href="link.href" @click.prevent="changeLink(index)">{{ link.label }}</a></li>
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
@use '../style/partials/mixins.scss' as *;

header{
  @include bg-img('../assets/img/jumbo-overlay.svg');
  background-color: var(--bg-primary-color);
  padding:20px;
  
  .header-top{
   display:flex;
   justify-content: space-between;
   color: var(--secondary-font-color);
  
   .bars{
    width:70%;
    display:flex;
    align-items:center;
    
    ul{
      display:flex;
      list-style:none;
      
      a{
        display: inline-block;
        padding:10px;
        text-decoration: none;
        cursor: pointer;
        &.active{
          background-color: var( --primary-color) ;
        }
      }
    }
  }
  .search-bar{
   background-color: var(--white);
   display: flex;
   justify-content: center;
   width:15%;
   border-radius: 5px;
   padding: 10px 5px;

    input{
      background: rgba(0,0,0,0);
      width:60%;
    }

    button{
      color: var(--primary-color);
      background-color: var(--white);
    }
  }
}
}
</style>
