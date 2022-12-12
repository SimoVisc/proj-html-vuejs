<script>
export default {
  name: 'AppSectionOnlineCertification ',
}
</script>

<template>
  <div class="bg-color">
  <div class="container">
    <img class="img-1" src="../assets/img/maxcoach-shape-01.png" alt="">
   <div class="text">
      <p> Start today for getting <span class="green-color">Online Certification</span> </p>
      <h3>You can be your own giuding star with our help!</h3>
    </div>  
    <button>Get started now</button>  
  <img class="img-2" src="../assets/img/maxcoach-shape-02.png" alt="">
</div>
 </div>
</template>
  
  <style lang="scss" scoped >
 .bg-color{
   background-color: var(--bg-primary-color);
   .container{
    width:100%;
    position:relative;
    text-align: center;
    padding-bottom: 30px;
   .text{
    padding: 20px;
    h3{
      color: var(--secondary-font-color)
    }
   }
   button{
      padding:10px 20px;
    }
    .img-1{
      position:absolute;
      top: 30%;
      left:0;
    }
    .img-2{
      width:10%;
      position:absolute;
      top: 40%;
      right:5%;
    }
  }
  }
  </style>