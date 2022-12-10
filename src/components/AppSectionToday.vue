<script>
export default {
  name: 'AppSection1',
}
</script>

<template>
  <section class="container">
      <div class="title">
         <small>START LEARNING CODING LANGUAGES</small>
         <h1>Build Your Dream <span class="green-color">TODAY</span></h1>
      </div>
      <div class="articles-container">
            <article>
                <div class="img-container"><img class="img-small" src="../assets/img/today-box-01.png" alt=""></div>
                <div class="text">
                    <h4>Idea Discussion</h4>
                    <p>Get teamed up with the specialists who work and teach coding for years at famous universities.</p>
                    <strong><a href="#">start now <i class="fa-solid fa-arrow-right"></i></a></strong>
                </div>
           </article>
            <article>

               <div class="img-container"> <img class="img-big" src="../assets/img/today-box-2.png" alt=""></div>
                <div class="text">
                    <h4>Web Development</h4>
                    <p>Learn to start building a webpage from scratch. You decide your own pace, course and speed.</p>
                    <strong><a href="#">start now <i class="fa-solid fa-arrow-right"></i></a></strong>
               </div>
            </article>
            <article>
                <div class="img-container"><img src="../assets/img/today-box-03.png" alt=""></div>
                <div class="text">
                    <h4>System Administration</h4>
                    <p>Learners are encouraged to study the mechanism and structure of system administration.</p>
                    <strong><a href="#">start now <i class="fa-solid fa-arrow-right"></i></a></strong>
               </div>
            </article>
            <article>
                <div class="img-container"><img src="../assets/img/today-box-04.png" alt=""></div>
                <div class="text">
                    <h4>Graphic Design</h4>
                    <p>Have a passion for graphics and arts? Show your talents with confidence and self-assertiveness.</p>
                    <strong><a href="#">start now <i class="fa-solid fa-arrow-right"></i></a></strong>
               </div>
            </article>
      </div>
    </section>
</template>

<style lang="scss" scoped >
    .articles-container{
        display: flex;
        padding-top: 50px;

        article{
        height:100%;
        padding: 10px;
        display:flex;
        flex-direction: column;
        .img-container{
          height:200px;
          display: flex;
          align-items: center;
          justify-content: center;
          margin:10px;

            img{
                width:60%;
            }
        }
            .text{
                display: flex;
                flex-direction: column;
            
                h4{
                height:50px;
                }
                p{
                flex-grow:1;
                }
                strong{
                height:50px;
                display: flex;
                align-items: flex-end;
                justify-content: center;

                a{
                color: var(--gray)
                }
            }
        }
       }
    }

</style>