<script>
export default {
  name: 'AppFooter',
}
</script>

<template>
  <div class="container">
  <div class="adress-container">
    <ul>
    <li><h2>Adress</h2></li>
    <li>382 NE 191st St # 87394 Miami, FL 33179-3899</li>
    <li>+1 (305) 547 - 9909 (9am -5pm EST,Monday - Friday)</li>
    <li> support@maxcoach.com</li>
    <li><div class="icon-container">
      facebook
    </div></li>
   </ul>
 </div>
 <div class="explore-container">
  <div class="col-1">
  <ul>
    <li><h2>Explore</h2></li>
    <li>Start here</li>
    <li>Blog</li>
    <li>About us</li>
  </ul>
  </div>
  <div class="col-2">
   <ul>
    <li> Succes story</li>
    <li> Courses</li>
    <li> Contact us</li>
    </ul>
  </div> 
  </div>
  <div class="information-container">
  <ul>
    <li><h2>Information</h2></li>
    <li>Membership</li>
    <li>Purchase guide</li>
    <li>Privacy policy</li>
    <li>Terms of service</li>
    </ul>
  </div>
</div>
</template>

<style lang="scss" scoped >
.container{
  display: flex;
  padding:50px;
  .adress-container{
    width: 50%;
  }
  .explore-container{
    width: 30%;
    display: flex;
    .col-1{
      width:50%;
    }
    .col-2{
      width:50%;
      padding-top:42px;
      margin-right:20px
    }
  }
  li{
    margin: 10px 0;
  }
}
</style>
