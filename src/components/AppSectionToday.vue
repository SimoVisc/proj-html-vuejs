<script>
export default {
  name: 'AppSection1',
}
</script>

<template>
  <section  >
      <div class="title">
         <small>START LEARNING CODING LANGUAGES</small>
         <h1>Build Your Dream<span class="green-color">TODAY</span></h1>
      </div>
      <div class="articles-container">
            <article>
                <img class="img-small" src="../assets/img/today-box-01.png" alt="">
                <div class="text">
                    <h4>Idea Discussion</h4>
                    <p>Get teamed up with the specialists who work and teach coding for years at famous universities</p>
                    <strong><a href="#">start now <i class="fa-solid fa-arrow-right"></i></a></strong>
                </div>
            </article>
            <article>
                <img class="img-big" src="../assets/img/today-box-2.png" alt="">
                <div class="text">
                    <h4>Web Development</h4>
                    <p>Learn to start building a webpage from scratch. You decide your own pace, course and speed</p>
                    <strong><a href="#">start now <i class="fa-solid fa-arrow-right"></i></a></strong>
               </div>
            </article>
            <article>
                <img src="../assets/img/today-box-03.png" alt="">
                <div class="text">
                    <h4>System Administration</h4>
                    <p>Learners are encouraged to study the mechanism and structure of system administration.</p>
                    <strong><a href="#">start now <i class="fa-solid fa-arrow-right"></i></a></strong>
               </div>
            </article>
            <article>
                <img src="../assets/img/today-box-04.png" alt="">
                <div class="text">
                    <h4>Graphic Design</h4>
                    <p>Have a passion for graphics and arts? Show your talents with confidence and self-assertiveness</p>
                    <strong><a href="#">start now <i class="fa-solid fa-arrow-right"></i></a></strong>
               </div>
            </article>
      </div>
    </section>
</template>

<style lang="scss" scoped >
    .articles-container{
        display: flex;
        padding: 50px 0;

        article{
            padding: 20px;
            flex-direction: column;
            align-items:flex-end;

            img{
                width:60%;
                padding: 10px 0;
                margin: 30px 0
            }
            .img-big{
                width: 47%
            }
            .img-small{
                width:65%
            }
            p{
            padding:20px
            }
            a{
            color: var(--grey)
            }
       }
    }

</style>