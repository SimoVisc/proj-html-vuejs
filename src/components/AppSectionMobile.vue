<script>
export default {
  name: 'AppSectionMobile',
}
</script>
<template>
  <section class="container">
   <div class="img-container">
    <img class="img-3" src="../assets/img/maxcoach-shape-01.png" alt="">
    <img class="img-2" src="../assets/img/underlay-shape-grey.svg" alt="">
    <img class="img-1" src="../assets/img/mobile-1.png" alt="">
    <img class="img-4" src="../assets/img/maxcoach-shape-07.png" alt="">
  </div>
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
   .img-container{
    width:60%;
    position:relative;
    display: flex;
    .img-1{
    width:53%;
    position:absolute;
    top:auto;
    left:25%;
  }
  .img-2{
    width:75%;
    padding-top:20px;
  }
   .img-3{
    position:absolute;
    top:40%;
    left:-20%;
   }
   .img-4{
    width:20%;
    height:80%;
    padding-top: 40%;
   }
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