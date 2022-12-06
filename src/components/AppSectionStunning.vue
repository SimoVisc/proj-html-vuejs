<script>
export default {
  name: 'AppSectionStunning',
}
</script>

<template>
  <section class="section2-top">
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
    <section class="section2-bottom ">
         <div class="number sessions">
              <strong class="green-color">1.926</strong>
              <small>FINISHED SESSIONS</small>
            </div>
            <div class="number learners">
              <strong class="green-color">3.092+</strong>
              <small>ENROLLED LEARNERS</small>
            </div>
            <div class="number instructors">
              <strong class="green-color">200</strong>
              <small>ONLINE INSTRUCTORS</small>
            </div>
            <div class="number satisfaction-rate">
              <strong class="green-color">100%</strong>
              <small>SATISFACTION RATE</small>
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
    .number{
        width: 25%;
        text-align: center;
        strong{
            display: block;
            font-size: 40px;
        }
    } 
}

</style>





