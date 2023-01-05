<script>
export default {
  name: "AppSectionToday",
  data() {
    return {
      cards: [
        {
          img: "-01",
          name: "Idea Discussion",
          task: "Get teamed up with the specialists who work and teach coding for years at famous universities.",
          href: "#",
        },
        {
          img: "-02",
          name: "Web Development",
          task: "Learn to start building a webpage from scratch. You decide your own pace, course and speed.",
          href: "#",
        },
        {
          img: "-03",
          name: "System Administration",
          task: "Learners are encouraged to study the mechanism and structure of system administration.",
          href: "#",
        },
        {
          img: "-04",
          name: "Graphic Design",
          task: "Have a passion for graphics and arts? Show your talents with confidence and self-assertiveness.",
          href: "#",
        },
      ],
    };
  },
};
</script>

<template>
  <section class="container">
    <div class="title">
      <small>START LEARNING CODING LANGUAGES</small>
      <h1>Build Your Dream <span class="green-color">TODAY</span></h1>
    </div>
    <div class="articles-container">
      <article v-for="card in cards">
        <div class="img-container">
          <img
            :src="`src/assets/img/today-box${card.img}.png`"
            :alt="card.name"
          />
        </div>
        <h4>{{ card.name }}</h4>
        <p>{{ card.task }}</p>
        <strong
          ><a :href="card.href"
            >start now <i class="fa-solid fa-arrow-right"></i></a
        ></strong>
      </article>
    </div>
  </section>
</template>

<style lang="scss" scoped>
.articles-container {
  display: flex;
  padding-top: 3.125rem;

  article {
    padding: 1.25rem;
    display: flex;
    flex-wrap: nowrap;
    flex-direction: column;

    .img-container {
      height: 9.375rem;
      margin: auto;

      img {
        width: 65%;
        padding: 1.25rem 0;
      }
    }

    h4 {
      height: 3.125rem;
      margin-top: 1.25rem;
    }

    p {
      flex-grow: 1;
    }

    strong {
      height: 3.125rem;
      display: flex;
      align-items: flex-end;
      justify-content: center;

      a {
        color: var(--gray);
      }
    }
  }
}
</style>
