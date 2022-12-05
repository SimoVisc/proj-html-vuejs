<script>
export default {
  name: 'AppMain',
}
</script>

<template>
  <main class="container">
     <article class="start-learning" >
        <small>START LEARNING CODING LANGUAGES</small>
        <div class="title">
            <h1>Build Your Dream</h1>
            <h1 class="green-color">TODAY</h1>
        </div>
        <div class="sections-container">
            <section>
                <img src="../assets/img/home-5-image-box-01.png" alt="">
                <h4>Idea Discussion</h4>
                <p>Get teamed up with the specialists who work and teach coding for years at famous universities</p>
                <a href="#">start now <i class="fa-solid fa-arrow-right"></i></a>
            </section>
            <section>
                <img class="img-big" src="../assets/img/home-5-image-box-02.png" alt="">
                <h4>Idea Discussion</h4>
                <p>Get teamed up with the specialists who work and teach coding for years at famous universities</p>
                <a href="#">start now <i class="fa-solid fa-arrow-right"></i></a>
            </section>
            <section>
                <img src="../assets/img/home-5-image-box-03.png" alt="">
                <h4>Idea Discussion</h4>
                <p>Get teamed up with the specialists who work and teach coding for years at famous universities</p>
                <a href="#">start now <i class="fa-solid fa-arrow-right"></i></a>
            </section>
            <section>
                <img src="../assets/img/home-5-image-box-04.png" alt="">
                <h4>Idea Discussion</h4>
                <p>Get teamed up with the specialists who work and teach coding for years at famous universities</p>
                <a href="#">start now <i class="fa-solid fa-arrow-right"></i></a>
            </section>
        </div>
 </article>
</main>
</template>

<style lang="scss">
.container{
    text-align: center;
    padding-top:40px;
    .title{
      display: flex;
      justify-content: center;
      margin:20px 0;
      .green-color{
         color: #62c5b5
        }
    }
    .sections-container{
        display: flex;
        align-items: center;
        padding: 80px 0;
       section{
        padding:10px;
        img{
            width:100px;
            padding: 10px 0;
            margin: 30px 0
        }
        .img-big{
            margin: 17px 0
        }
        p{
            padding:20px 0
        }
        a{
          color:gray;
        }
       }
        
    }
}
</style>
