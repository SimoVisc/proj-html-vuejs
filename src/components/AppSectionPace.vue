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
    <img class="img-1" src="../assets/img/pace-01.png" alt="">
    <img class="img-2" src="../assets/img/underlay-shape-grey.svg" alt="">
    <img  class="img-3" src="../assets/img/maxcoach-shape-05.png" alt="">
  </section>
</template>
  
  <style lang="scss" scoped >
  section{
    position:relative;
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
        padding: 10px 20px;
        margin:20px;
      }
    }
    .img-1{
    width:40%;
    position:absolute;
    top:auto;
    left:50%;
  }
  .img-2{
    width:40%;
    padding-top:100px;
  }
  .img-3{
    width:15%;
    position:absolute;
    top:55%;
    right: 0;
  }
  }
  
  </style>
  