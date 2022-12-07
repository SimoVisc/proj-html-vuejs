<script>
export default {
  name: 'AppAccordion',
  data() {
    return {
      accordions: [
        {
          titleButton: 'Multiple Platforms Supported for Teaching & Studying',
          textPanel: 'MaxCoach supports the act of teaching and learning on multiple platforms',
          open: true
        },
        {
          titleButton: 'Multiple Course Partecipation at the Same Time',
          textPanel: 'MaxCoach supports the act of teaching and learning on multiple platforms',
          open: false
        },
        {
          titleButton: 'Track Study Progress & Deliver Prompt Feedback',
          textPanel: 'MaxCoach supports the act of teaching and learning on multiple platforms',
          open: false
        }
      ]
    };
  },
  methods: {
    openAccordion(index) {
      this.accordions.forEach((elm, i) => {
        if (i === index) {
         elm.open = true;
        } else {
          elm.open = false;
        }
     });
    },
  }
}
</script>

<template>
<div class="accordions-container" v-for=" (item,index) in accordions">
  <button
  :class="{open: item.open}"  
  @click.prevent="openAccordion(index)"
  class="accordion">
  {{ item.titleButton }}</button>
  <p class="panel"> {{item.textPanel}}</p>
</div>
</template>


<style lang="scss" scoped>
.accordion {
      width:100%;
      text-align: start;
      background-color: #fff;
      color:var(--gray);
      cursor: pointer;
      padding:10px;
      margin:20px;
      border: none;
      outline: none;
      transition: 0.4s;
      box-shadow: 0 4px 8px 0 rgba(0, 0, 0, 0.2);
    }
    // &.open{
    .accordion:hover{
     background-color: var(--primary-color);
     color:#fff
    }
    .panel {
      padding: 0 18px;
      background-color: #fff;
      display: none;
      overflow: hidden;
    }
  
</style>