<template>
  <div>
    <h2>COURSES </h2>
    <!-- All courses -->
    <div id="card" class="card" style="width: 18rem;"><img src="../assets/images/brain-color-colorful-cube-19677.jpg"
        class="card-img-top" style="width: 18rem; height: 13rem; justify-item: center;" alt="...">
      <div class="card-body">
        <h5 class="card-title">Mathematics</h5><small class="card-text">Learn all the basics of Pythagoras theorem
          <br>21/07/2020 <br>2hrs 30mins </small><br><a href="" class="btn btn-danger">Watch now</a>
      </div>
    </div>
    <!-- The blue rectangle part -->
    <div class="blue-rectangle">
        <h1 id="main">GET PERSONAL LEARNING GUIDE</h1>
        <h3 id="main2">subscribe now and get a private tutor</h3>
        <button id="subscribe"><a href="#">SUBSCRIBE NOW</a></button>
    </div>
    <h2>TOP COURSES </h2>
    <!-- Top courses -->
    <div id="card" class="card" style="width: 18rem;"><img src="../assets/images/brain-color-colorful-cube-19677.jpg"
        class="card-img-top" style="width: 18rem; height: 13rem; justify-item: center;" alt="...">
      <div class="card-body">
        <h5 class="card-title">Mathematics</h5><small class="card-text">Learn all the basics of Pythagoras theorem
          <br>21/07/2020 <br>2hrs 30mins </small><br><a href="" class="btn btn-danger">Watch now</a>
      </div>
    </div>
  </div>
</template>
<script>
  export default {}

</script>
<style scoped>
  h2 {
    padding-left: 60px;
    margin-bottom: 40px;
    font-family: montserrat;
    color: #2f80ed;
  }

  #card {
    clear: both;
    display: inline-block;
    margin-bottom: 20px;
    margin-right: 20px;
    margin-left: 60px;
    align-self: center;
    justify-content: center;

  }

  #card:hover {
    -webkit-transform: scale(1.05);
    -ms-transform: scale(1.05);
    transform: scale(1.05);
    transition: ease-in 0.3s;
  }

  .card-title {
    font-weight: 700;
  }

  .blue-rectangle {
    width: 100%;
    height: 328px;
    left: 0px;

    background: #2D9CDB;
  }
  @media (max-width: 858px) {
  .blue-rectangle {
      display: flexbox;
      flex-shrink: inherit;
  }
}
h1 {
    position: relative;
    width: 650px;
    height: 35px;
    left: 360px;
    padding-top: 78px;
    font-family: Cardo;
    font-style: normal;
    font-weight: bold;
    font-size: 38px;
    line-height: 92.69%;
    /* or 35px */

    text-align: center;

    color: #EDE9E9;
}
h3 {
    position: relative;
    width: 570px;
    height: 35px;
    left: 403px;
    top: 50px;

    font-family: Cardo;
    font-style: normal;
    font-weight: normal;
    font-size: 38px;
    line-height: 92.69%;
    /* or 35px */

    text-align: center;

    color: #383838;
}
#subscribe{
    position: relative;
    width: 385px;
    height: 66px;
    left: 500px;
    top: 53px;
    border: none;
    background: #FFFFFF;
}
button>a {
    font-family: Cardo;
    font-style: normal;
    font-weight: bold;
    font-size: 38px;
    line-height: 92.69%;
    /* or 35px */

    text-align: center;

    color: #363636;
}
</style>
