<script>
export default {
  name: 'AppSectionCourses',
}
</script>

<template>
  <div class="title">
    <small>CHOOSE WHERE YOU'D LIKE TO BEGIN</small>
    <h1>Latest Featured <span class="green-color">Courses</span></h1>
  </div>
  <div class="articles-container">
    <article>
      <img class="main-image" src="../assets/img/course-1.jpg" alt="">
      <div class="price">$40.00</div>
      <div class="text">
        <div class="writer">
          <img class="img-writer" src="../assets/img/73ee246daf47502812ccefc84bf02898.jpeg" alt="">
          <small> Blanche Fields</small>
        </div>
        <h5>Learning to Write as a Professional Author </h5> 
        <div class="view-container">
        <small> <i class="fa-solid fa-file"></i>  20 Lessons</small>
        <small> <i class="fa-solid fa-user"></i> 50 students</small>
        </div>
     </div>
    </article>
    <article>
      <img class="main-image" src="../assets/img/course-2.jpg" alt="">
      <div class="price">Free</div>
      <div class="text">
        <div class="writer">
          <img class="img-writer" src="../assets/img/73ee246daf47502812ccefc84bf02898.jpeg" alt="">
          <small> Maggie Stickland</small>
        </div>
        <h5>Customer-centric Info-Tech Strategies </h5> 
        <div class="view-container">
        <small> <i class="fa-solid fa-file"></i>  24 Lessons</small>
        <small> <i class="fa-solid fa-user"></i> 769 students</small>
        </div>
     </div>
    </article>
    <article>
      <img class="main-image" src="../assets/img/course-3.jpg" alt="">
      <div class="price">$19.00</div>
      <div class="text">
        <div class="writer">
          <img class="img-writer" src="../assets/img/73ee246daf47502812ccefc84bf02898.jpeg" alt="">
          <small>  Maggie Stickland</small>
        </div>
        <h5>Open Programming Courses for Everyone: Python </h5> 
        <div class="view-container">
        <small> <i class="fa-solid fa-file"></i>  17 Lessons</small>
        <small> <i class="fa-solid fa-user"></i> 62 students</small>
        </div>
     </div>
    </article>
    <article>
      <img class="main-image" src="../assets/img/course-4.jpg" alt="">
      <div class="price">$26.00</div>
      <div class="text">
        <div class="writer">
          <img class="img-writer" src="../assets/img/73ee246daf47502812ccefc84bf02898.jpeg" alt="">
          <small> Blanche Fields</small>
        </div>
        <h5>Academic Listening and Note-taking </h5> 
        <div class="view-container">
        <small> <i class="fa-solid fa-file"></i>  14 Lessons</small>
        <small> <i class="fa-solid fa-user"></i> 67 students</small>
        </div>
     </div>
    </article>
    <article>
      <img class="main-image" src="../assets/img/course-5.jpg" alt="">
      <div class="price">$39.00</div>
      <div class="text">
        <div class="writer">
          <img class="img-writer" src="../assets/img/73ee246daf47502812ccefc84bf02898.jpeg" alt="">
          <small> Blanche Fields</small>
        </div>
        <h5>Master jQuery in a Short Period of Time </h5> 
        <div class="view-container">
        <small> <i class="fa-solid fa-file"></i>  6 Lessons</small>
        <small> <i class="fa-solid fa-user"></i> 51 students</small>
        </div>
     </div>
    </article>
    <article>
      <img class="main-image" src="../assets/img/course-6.jpg" alt="">
      <div class="price">$59.00</div>
      <div class="text">
        <div class="writer">
          <img class="img-writer" src="../assets/img/73ee246daf47502812ccefc84bf02898.jpeg" alt="">
          <small> Blanche Fields</small>
        </div>
        <h5>Introduction of Javascript for Beginners </h5> 
        <div class="view-container">
        <small> <i class="fa-solid fa-file"></i>  14 Lessons</small>
        <small> <i class="fa-solid fa-user"></i> 50 students</small>
        </div>
     </div>
    </article>
  </div>
</template>

<style lang="scss" scoped >
.title{
text-align: center;
padding-top: 40px;
}.articles-container{
  display: flex;
  flex-wrap: wrap;
  padding-top: 20px;
   
  article{
    width:calc(100% / 3);

    .main-image{
      width:80%;
      padding-top:35px ;
      position: relative;
    }
    .price{
      background-color: #62c5b5;
      position:absolute;
      bottom:20px;
      right:20px
    }
  
    .text{
      padding:10px;
      
      .writer{
       display:flex;
       align-items: center;
        .img-writer{
          width:6%;
          margin-right:3px;
          border-radius: 50px;
        }
      }
      small{
        color:#7a7a7a;
        padding-right:5px
      }
      h5{
        font-size:18px;
        padding:10px 0;
      }
    }
  }
}
</style>