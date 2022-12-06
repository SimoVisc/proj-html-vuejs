<script>
export default {
  name: 'AppSectionStunning',
}
</script>

<template>
  <section>
    <div class="section-top">
      <img class="img-1" src="../assets/img/underlay-shape-lilla.svg" alt="">
      <img class="img-2" src="../assets/img/stunning-1.png" alt="">
      <div class="text">
        <div class="title">
          <small>DREAM WITH <strong>MAXCOACH</strong></small>
          <h1>Construct A <span class="green-color">Stunning</span> Career Prospective </h1>
        </div>
        <div class="accordions-container">
          <button class="accordion">Multiple Platforms Supported for Teaching & Studying</button>
          <div class="panel">
              <p>MaxCoach supports the act of teaching and learning on multiple platforms</p>
          </div>
        </div>
        <div class="accordions-container">
          <button class="accordion">Multiple Course Partecipation at the Same Time</button>
          <div class="panel">
            <p>MaxCoach supports the act of teaching and learning on multiple platforms</p>
          </div>
        </div>
        <div class="accordions-container">
          <button class="accordion">Track Study Progress & Deliver Prompt Feedback</button>
          <div class="panel">
            <p>MaxCoach supports the act of teaching and learning on multiple platforms</p>
          </div>
        </div>
     </div>
   </div>
   <div class="section-bottom">
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
   </div>
  </section>
</template>

<style lang="scss" scoped >
.section-top{
  display:flex;
  .img-1{
    position:relative;
    width:30%;
    top:auto;
    left:auto;
  }
  .img-2{
    position:absolute;
    top:auto;
    left:auto;
  }
  .text{
   width:50%;
   padding: 30px;
   margin-left: 20%;
   text-align: start;
   .title{
     margin:20px ;
    }
    .accordion {
      width:100%;
      text-align: start;
      background-color: #fff;
      color:var(--gray);
      cursor: pointer;
      padding:10px;
      margin:20px;
      border: none;
      outline: none;
      transition: 0.4s;
      box-shadow: 0 4px 8px 0 rgba(0, 0, 0, 0.2);
    }
    .accordion:hover {
     background-color: var(--primary-color);
     color:#fff
    }
    .panel {
      padding: 0 18px;
      background-color: #fff;
      display: none;
      overflow: hidden;
    }
  } 
}   
.section-bottom{
  display:flex;
  background-color: var(--bg-primary-color);
  padding:20px;
  margin-top: 15%;
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





