<script>
import AppAccordion from "./AppAccordion.vue";
export default {
  name: "AppSectionStunning",
  components: {
    AppAccordion,
  },
  data() {
    return {
      data: [
        {
          number: "1.926",
          name: "FINISHED SESSIONS",
        },
        {
          number: "3.092+",
          name: "ENROLLED LEARNERS",
        },
        {
          number: "200",
          name: "ONLINE INSTRUCTORS",
        },
        {
          number: "100%",
          name: "SATISFACTION RATE",
        },
      ],
    };
  },
};
</script>

<template>
  <section class="container">
    <div class="section-top">
      <div class="img-container">
        <img
          class="img-1"
          src="../assets/img/underlay-shape-lilla.svg"
          alt=""
        />
        <img class="img-2" src="../assets/img/stunning-1.png" alt="" />
      </div>
      <div class="text">
        <div class="title">
          <small>DREAM WITH <strong>MAXCOACH</strong></small>
          <h1>
            Construct A <span class="green-color">Stunning</span> Career
            Prospective
          </h1>
        </div>
        <AppAccordion />
      </div>
    </div>
  </section>
  <div class="bg-img">
    <section class="section-bottom container">
      <div class="data" v-for="item in data">
        <strong class="green-color number">{{ item.number }}</strong>
        <small>{{ item.name }}</small>
      </div>
    </section>
  </div>
</template>

<style lang="scss" scoped>
.section-top {
  display: flex;
  .img-container {
    width: 50%;
    position: relative;
    .img-1 {
      height: 60%;
      position: absolute;
      top: 3rem;
      right: 7rem;
    }
    .img-2 {
      height: 75%;
      position: relative;
      top: auto;
      left: 1.625rem;
    }
  }
  .text {
    width: 50%;
    padding: 0 1.25rem;

    .title {
      padding-bottom: 3.125rem;
      text-align: start;
    }
  }
}
.bg-img {
  background-color: var(--bg-primary-color);
  .section-bottom {
    display: flex;
    justify-content: space-between;
    padding: 1.25rem;
    margin-top: 15%;

    .data {
      text-align: center;
    }
    .number {
      display: block;
      font-size: 2.5rem;
    }
  }
}
</style>
