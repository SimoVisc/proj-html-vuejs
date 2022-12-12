<script>
export default {
  name: 'AppSectionEvents',
}
</script>

<template>
    <section class="container">
        <div class="title">
            <small>GET IN CONTACT NOW</small>
            <h1>Upcoming<span class="green-color">Events</span></h1>
        </div>
        <div class="event-container">
            <div class="event-info">
            <small> <i class="fa-solid fa-location-dot"></i> Texas, US </small>
            <h5>Storytellig Workshop</h5>
            </div>
            <div class="event-date">
                <div class="green-color number"> 22</div>
                <span>NOV</span>
                <button>Get ticket</button>
            </div>
       </div>
       <div class="event-container">
            <div class="event-info">
            <small> <i class="fa-solid fa-location-dot"></i> New York, US </small>
            <h5>Painting Art Contest 2020</h5>
            </div>
            <div class="event-date">
                <div class="green-color number"> 10</div>
                <span>OCT</span>
                <button>Get ticket</button>
            </div>
       </div>
       <div class="event-container">
            <div class="event-info">
            <small> <i class="fa-solid fa-location-dot"></i> Hamburg, Germany </small>
            <h5>International Art Fair 2020</h5>
            </div>
            <div class="event-date">
                <div class="green-color number"> 23</div>
                <span>NOV</span>
                <button>Get ticket</button>
            </div>
       </div>
       <div class="event-container">
            <div class="event-info">
            <small> <i class="fa-solid fa-location-dot"></i> Illinois, US </small>
            <h5>Street Performance: Call for Artist</h5>
            </div>
            <div class="event-date">
                <div class="green-color number"> 15</div>
                <span>DEC</span>
                <button>Get ticket</button>
            </div>
       </div>
       <div class="event-container">
            <div class="event-info">
            <small> <i class="fa-solid fa-location-dot"></i>Illinois, US </small>
            <h5>Consumer Food Safety Education Conference</h5>
            </div>
            <div class="event-date">
                <div class="green-color number"> 22</div>
                <span>JUL</span>
                <button>Get ticket</button>
            </div>
       </div>
       <div class="event-container">
            <div class="event-info">
            <small> <i class="fa-solid fa-location-dot"></i> Dubai </small>
            <h5>How meditation improve your mental health</h5>
            </div>
            <div class="event-date">
                <div class="green-color number"> 12</div>
                <span>AUG</span>
                <button>Get ticket</button>
            </div>
       </div>
       <span class="link-event">Exited about our event? <a class="green-color" href="#"> view all events <i class="fa-solid fa-arrow-right"></i> </a></span>
  </section>
</template>
  
  <style lang="scss" scoped >
  section{
   display:flex;
   justify-content:center;
   flex-wrap: wrap;
  
   .title{
    width:100%;
    text-align: center;
   }
   .event-container{
    width: 40%;
    background-color: #f8f8f8 ;
    display: flex;
    margin: 20px;
    padding:20px;


    .event-info{
        padding-right:20%;
        text-align: start;
    }
    .event-date{
        width:30%;
        margin-left:auto;
        .number{
            font-size: 50px;
        }
        button{
        padding:10px;
      }
    }
   }
   .link-event{
    margin: 50px 0
   }
}
  
  </style>