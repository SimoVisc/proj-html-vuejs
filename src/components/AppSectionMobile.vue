<script>
export default {
  name: 'AppSectionMobile',
}
</script>
<template>
  <section class="container">
    <img src="../assets/img/mobile-1.png" alt="">
    <div class="text">
      <div class="title">
        <small>WHAT ARE YOU LOOKING FOR?</small>
        <h1>Learn On Your <span class="green-color">mobile</span> anytime!</h1>
      </div>
      <p>Save lessons for later and revise or write notes at any time and on multiple devices on your way. Never interfere with activities og enjoyment on other precious moments</p> 
      <button>Download Our App</button>
    </div>
  </section>
</template>
  
  <style lang="scss" scoped >
  section{
   display: flex;
   text-align: start;
   
    img{
    width:50%;
    padding-right:50px;
    }
    .text{
      width:40%;
      p{
        padding: 20px 0
      }
      button{
        padding:10px 20px;
      }
    }
    
  }
  
  </style>