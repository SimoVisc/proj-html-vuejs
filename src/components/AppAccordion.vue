<script>
export default {
  name: "AppAccordion",
  data() {
    return {
      activeAccordion: 0,
      accordions: [
        {
          title: "Multiple Platforms Supported for Teaching & Studying",
          textPanel:
            "MaxCoach supports the act of teaching and learning on multiple platforms",
          open: true,
        },
        {
          title: "Multiple Course Partecipation at the Same Time",
          textPanel:
            "MaxCoach supports the act of teaching and learning on multiple platforms",
          open: false,
        },
        {
          title: "Track Study Progress & Deliver Prompt Feedback",
          textPanel:
            "MaxCoach supports the act of teaching and learning on multiple platforms",
          open: false,
        },
      ],
    };
  },
  methods: {
    showOpenAccordion(index) {
      this.accordions.forEach((elm, i) => {
        if (i === index) {
          elm.open = true;
        } else {
          elm.open = false;
        }
      });
    },
  },
};
</script>

<template>
  <div
    class="accordions-container"
    v-for="(accordion, index) in accordions"
    :class="{ open: accordion.open }"
    @click="showOpenAccordion(index)"
  >
    <div class="accordion">
      {{ accordion.title }}
    </div>
    <p class="panel" v-show="accordion.open">
      {{ accordion.textPanel }}
    </p>
  </div>
</template>

<style lang="scss" scoped>
.accordion {
  width: 100%;
  text-align: start;
  background-color: var(--white);
  color: var(--gray);
  cursor: pointer;
  padding: 10px;
  margin: 20px 0;
  border: none;
  outline: none;
  transition: 0.4s;
  box-shadow: 0 4px 8px 0 rgba(0, 0, 0, 0.2);
}
.open .accordion {
  background-color: var(--primary-color);
  color: var(--white);
  margin: 0;
}
.panel {
  background-color: #fff;
  box-shadow: 0 4px 8px 0 rgba(0, 0, 0, 0.2);
  overflow: hidden;
  width: 100%;
  text-align: start;
  background-color: var(--white);
  cursor: pointer;
  padding: 10px;
  border: none;
  outline: none;
}
</style>
