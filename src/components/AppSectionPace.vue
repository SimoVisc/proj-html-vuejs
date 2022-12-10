<script>
export default {
  name: 'AppSectionPace',
}
</script>

<template>
  <section class="container">
    <div class="text">
      <div class="title">
         <small>WHY ESITATE TO REGISTER?</small>
         <h1>Learn At Your Own <span class="green-color">Pace</span></h1>
      </div>
      <ul>
        <li><i class="green-color fa-solid fa-check"></i>Select and customize courses</li>
        <li><i class="green-color fa-solid fa-check"></i>Change the tutor and make arrangement</li>
        <li><i class="green-color fa-solid fa-check"></i>Partecipate in events to join others</li>
        <li><i class="green-color fa-solid fa-check"></i>Get the desired certificate delivered at hause</li>
      </ul>
      <button>Get started for free</button>
    </div>
    <img src="../assets/img/pace-01.png" alt="">
  </section>
</template>
  
  <style lang="scss" scoped >
  section{
   width:100%;
   display: flex;
   padding-top:40px;
   .text{
    width:40%;
    text-align: start;

     li{
      padding:10px 0;
      
      i{
        padding-right: 10px;
      }
     }
     button{
        padding:10px 20px;
      }
    }
    img{
      width:40%;
    }
  }
  
  </style>
  