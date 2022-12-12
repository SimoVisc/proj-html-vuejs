<script>
export default {
  name: 'AppSectionCourses',
}
</script>

<template>
  <div class="bg-img">
    <section class="container">
    <div class="title">
      <small>CHOOSE WHERE YOU'D LIKE TO BEGIN</small>
      <h1>Latest Featured <span class="green-color">Courses</span></h1>
    </div>
    <div class="articles-container">
      <article>
        <div class="price"><strong>$40.00</strong></div>
        <img class="main-image" src="../assets/img/course-1.jpg" alt="">
        
        <div class="text">
          <div class="writer">
            <img class="img-writer" src="../assets/img/writer-1.jpeg" alt="">
            <small> Blanche Fields</small>
          </div>
          <h5>Learning to Write as a Professional Author </h5> 
          <div class="view-container">
          <small> <i class="fa-regular fa-file-lines"></i> 20 Lessons</small>
          <small> <i class="fa-regular fa-user"></i> 50 students</small>
          </div>
      </div>
      </article>
      <article>
        <div class="price"><strong>Free</strong></div>
        <img class="main-image" src="../assets/img/course-2.jpg" alt="">
        <div class="text">
          <div class="writer">
            <img class="img-writer" src="../assets/img/writer-2.jpeg" alt="">
            <small> Maggie Stickland</small>
          </div>
          <h5>Customer-centric Info-Tech Strategies </h5> 
          <div class="view-container">
          <small> <i class="fa-regular fa-file-lines"></i>  24 Lessons</small>
          <small> <i class="fa-regular fa-user"></i> 769 students</small>
          </div>
      </div>
      </article>
      <article>
        <div class="price"><strong>$19.00</strong></div>
        <img class="main-image" src="../assets/img/course-3.jpg" alt="">
        <div class="text">
          <div class="writer">
            <img class="img-writer" src="../assets/img/writer-2.jpeg" alt="">
            <small>  Maggie Stickland</small>
          </div>
          <h5>Open Programming Courses for Everyone: Python </h5> 
          <div class="view-container">
          <small> <i class="fa-regular fa-file-lines"></i> 17 Lessons</small>
          <small> <i class="fa-regular fa-user"></i> 62 students</small>
          </div>
      </div>
      </article>
      <article>
        <div class="price"><strong>$26.00</strong></div>
        <img class="main-image" src="../assets/img/course-4.jpg" alt="">
        <div class="text">
          <div class="writer">
            <img class="img-writer" src="../assets/img/writer-1.jpeg" alt="">
            <small> Blanche Fields</small>
          </div>
          <h5>Academic Listening and Note-taking </h5> 
          <div class="view-container">
          <small> <i class="fa-regular fa-file-lines"></i>  14 Lessons</small>
          <small> <i class="fa-regular fa-user"></i> 67 students</small>
          </div>
      </div>
      </article>
      <article>
        <div class="price"><strong>$39.00</strong></div>
        <img class="main-image" src="../assets/img/course-5.jpg" alt="">
        <div class="text">
          <div class="writer">
            <img class="img-writer" src="../assets/img/writer-1.jpeg" alt="">
            <small> Blanche Fields</small>
          </div>
          <h5>Master jQuery in a Short Period of Time </h5> 
          <div class="view-container">
          <small> <i class="fa-regular fa-file-lines"></i>  6 Lessons</small>
          <small> <i class="fa-regular fa-user"></i> 51 students</small>
          </div>
      </div>
      </article>
      <article>
        <div class="price"><strong>$59.00</strong></div>
        <img class="main-image" src="../assets/img/course-6.jpg" alt="">
        <div class="text">
          <div class="writer">
            <img class="img-writer" src="../assets/img/writer-1.jpeg" alt="">
            <small> Blanche Fields</small>
          </div>
          <h5>Introduction of Javascript for Beginners </h5> 
          <div class="view-container">
          <small> <i class="fa-regular fa-file-lines"></i> 14 Lessons</small>
          <small> <i class="fa-regular fa-user"></i> 50 students</small>
          </div>
      </div>
      </article>
    </div>
    <div class="btn-container">
      <button>View all courses  <i class="fa-solid fa-arrow-right"></i></button>
    </div>
  </section>
  </div>
</template>

<style lang="scss" scoped >
.bg-img{
  background-image: url(../assets/img/close.svg) ;
  background-color: #fcfcfc;
 
}
.title{
text-align: center;
padding-top: 40px;
}.articles-container{
  display: flex;
  flex-wrap: wrap;
  justify-content: space-between;

  article{
    width:calc(100% / 3);
    position:relative;
    left:auto;
    bottom: auto;
    padding-top: 50px;
    .main-image{
      display: block;
      width:80%;
    }
    .price{
      width:20%;
      color:#fff;
      background-color: var(--primary-color);
      position:absolute;
      left: 180px;
      bottom:auto;
      padding:5px;
    }
    .text{
      width:80%;
      padding-top:10px;
      padding-left:10px;
      text-align:start;
      .writer{
       display: flex;
       align-items: center;
       .img-writer{
          width:6%;
          margin-right:3px;
          border-radius: 50px;
        }
      }
      small{
        padding-right:5px;
        .fa-user{
          margin-left:20px;
        }
      }
      h5{
        font-size:18px;
        padding:10px 0;
      }
    }
  }
}
.btn-container{
  width:100%;
  text-align: center;
  padding: 50px 0;
  button{
    padding:10px 20px;
  }
}
</style>