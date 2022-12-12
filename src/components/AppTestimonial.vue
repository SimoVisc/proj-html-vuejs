<script>
export default {
  name: 'AppTestimonial',
  data() {
    return {
      activeContact:0,
      testimonials: [
        {
          img: '-01.jpg',
          text: 'I am free to learn at my own pace, follow my own schedule and choose the subject i like. Great study portal for people.',
          name: 'MINA HOLLACE',
          job: '/Freelancer'
        },
        {
          img: '-02.jpg',
          text: 'MaxCoach is my best choise. their tutors are smart and professional when dealing with students.',
          name: 'MADLEY PONDOR',
          job: '/IT specialist'
        },
        {
          img: '-03.jpg',
          text: 'I am happy with their arrangement of lessons and subjects. They reflect a scientific investigation.',
          name: 'LUVIC DUBBLE',
          job: '/Private Tutor'
        },
        // {
        //   img: '-04.jpg',
        //   text: 'I am happy with their arrangement of lessons and subjects. They reflect a scientific investigation.',
        //   name: 'STEVE KARL',
        //   job: '/Doctor'
        // }
      ]
    };
  },
  methods:{
        showActiveContact(i){
            this.activeContact = i;
        },
     }, 
  }
</script>

<template>

<div class="testimonial-container" v-for=" testimonial in testimonials">
    <img :src="`assets/img/testimonial-avatar${testimonial.img}`" alt="">
    <div class="text">
        <p>{{ testimonial.text}}</p>
        <strong>{{testimonial.name}}</strong>
        <small>{{testimonial.job}}</small>
    </div>
</div>
</template>


<style lang="scss" scoped>
.testimonial-container{
    background-color: #fff;
      position: relative;
      width: calc(100% / 3);
      margin:20px;
      box-shadow: 0 4px 8px 0 rgba(0, 0, 0, 0.2);
      text-align: center;
      
    img{
       position:absolute;
       left: 30%;
       top: -28%;
       width: 40%;
       border-radius: 50%;
    }
    .text{
        margin-top:30px;
        p{
          padding:20px
        }
        strong{
          display:block;
          padding:10px
        }
    }
}
</style>