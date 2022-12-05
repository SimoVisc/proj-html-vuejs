<script>
export default {
  name: 'AppSection2',

}

      

</script>

<template>
  <section class="section2">
    <img src="../assets/img/about-us-03-image-01.png" alt="">
      <div class="text-container">
          <div class="title">
             <small>DREAM WITH <strong>MAXCOACH</strong></small>
             <h1>Construct A <span class="green-color">Stunning</span> Career Prospective </h1>
          </div>

          <button class="accordion">Multiple Platforms Supported for Teaching & Studying</button>
          <div class="panel">
             <p>MaxCoach supports the act of teaching and learning on multiple platforms</p>
          </div>

          <button class="accordion">Multiple Course Partecipation at the Same tTime</button>
          <div class="panel">
             <p>MaxCoach supports the act of teaching and learning on multiple platforms</p>
          </div>

          <button class="accordion">Track Study Progress & Deliver Prompt Feedback</button>
          <div class="panel">
             <p>MaxCoach supports the act of teaching and learning on multiple platforms</p>
          </div>
        </div>
  </section>
</template>

<style lang="scss" scoped >
section{
   width:100%;
   display: flex;
   padding-top:40px;

   img{
        width:50%;
        padding:20px
    }
    .text-container{
     padding-left: 30px;
     
    .title{
      margin:20px 0;

      .green-color{
         color: #62c5b5
        }
    }
   .accordion {
        background-color: #fff;
        color: #696969;
        cursor: pointer;
        padding: 10px;
        

        border: none;
        outline: none;
        transition: 0.4s;
    }
    .accordion:hover {
     background-color: #62c5b5;
     color:#fff
    }
    .panel {
    padding: 0 18px;
    background-color: white;
    display: none;
    overflow: hidden;
    }
}
}
</style>





