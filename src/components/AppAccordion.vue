<script>
export default {
  name: 'AppAccordion',
  data() {
    return {
      activeAccordion:0,
      accordions: [
        {
          title: 'Multiple Platforms Supported for Teaching & Studying',
          textPanel: 'MaxCoach supports the act of teaching and learning on multiple platforms',
          open: true
        },
        {
          title: 'Multiple Course Partecipation at the Same Time',
          textPanel: 'MaxCoach supports the act of teaching and learning on multiple platforms',
          open: false
        },
        {
          title: 'Track Study Progress & Deliver Prompt Feedback',
          textPanel: 'MaxCoach supports the act of teaching and learning on multiple platforms',
          open: false
        }
      ]
    };
  },
  methods: {
    showActiveAccordion(index){
      this.activeAccordion = i;
    }
  },
}
</script>

<template>
<div 
 class="accordions-container" 
 v-for="(accordion, index) in accordions" 
 :class="{active: index === activeAccordion}"
 > 
 <button
  @click="showActiveAccordion(index)"  
  class="accordion" >
  {{ accordion.title }}</button>
 <p class="panel"  v-show="accordion === true">{{accordion.textPanel}}</p>
</div>
</template>


<style lang="scss" scoped>
.accordion {
      width:100%;
      text-align: start;
      background-color: var(--white);
      color:var(--gray);
      cursor: pointer;
      padding:10px;
      margin:20px;
      border: none;
      outline: none;
      transition: 0.4s;
      box-shadow: 0 4px 8px 0 rgba(0, 0, 0, 0.2);
    }
    .accordion:hover{     
    background-color: var(--primary-color);      
    color: var(--white)
}
.panel {
padding: 0 18px;
background-color: #fff;
display: none;
 overflow: hidden;
}

</style>