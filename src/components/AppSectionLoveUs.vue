<script>
export default {
  name: 'AppSectionLoveUs',
}
</script>

<template>
    <section>
        <div class="title">
            <small>PEOPLE ARE PRAISING MAXCOACH</small>
            <h1>What make they <span class="green-color">love us?</span></h1>
        </div>
        <div class="testimonials">
          <div class="testimonial-container">
             <img src="../assets/img/testimonial-avata-02.jpg" alt="">
             <p>I am free to learn at my own pace, follow my own schedule and choose the subject i like. Great study portal for people like me</p>
             <strong>MINA HOLLACE</strong>
             <small>/Freelancer</small>
           </div>
           <div class="testimonial-container">
             <img src="../assets/img/testimonial-avata-03.jpg" alt="">
             <p>MaxCoach is my best choise. their tutors are smart and professional when dealing with students.</p>
             <strong>MADLEY PONDOR</strong>
             <small>/IT specialist</small>
           </div>
           <div class="testimonial-container">
             <img src="../assets/img/testimonial-avata-01.jpg" alt="">
             <p>I am happy with their arrangement of lessons and subjects. They reflect a scientific investigation.</p>
             <strong>LUVIC DUBBLE</strong>
             <small>/Private Tutor</small>
           </div>
        </div>
           
       
  </section>
</template>
  
  <style lang="scss" scoped >
  section{
   width:100%;
   padding-top:40px;
   .title{
    width:100%;
    text-align: center;
   }
   .testimonials{
    width:100%;
    display:flex;
    padding:20px;
    .testimonial-container{
        width: calc(100% / 3);
        margin:20px;
        box-shadow: 0 4px 8px 0 rgba(0, 0, 0, 0.2);
        text-align: center;
        img{
 
  border-radius: 50%;
  
  width: 200px;

        }
        p{
            padding:20px
        }
        strong{
            display:block;
            padding:10px
        }
    }
   }
   }
   img{
    width:50%;
    padding-right: 40px
   }
  
  
  </style>