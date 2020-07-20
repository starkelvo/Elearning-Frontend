<template>
  <div>
    <div class="wrap-courses">
    <h2>COURSES </h2>
    <!-- All courses -->
    <div id="card" class="card" ><img src="../assets/images/brain-color-colorful-cube-19677.jpg"
        class="card-img-top" alt="...">
      <div class="card-body">
        <h5 class="card-title">Mathematics</h5><small class="card-text">Learn all the basics of Pythagoras theorem
          <br>21/07/2020 <br>2hrs 30mins </small><br><a href="" class="btn btn-danger">Watch now</a>
      </div>
    </div>
    <!-- The blue rectangle part -->
    <div class="blue-rectangle">
        <div class="sub-wrap">
        <h1 id="main">GET PERSONAL LEARNING GUIDE</h1>
        </div>
          <div class="sub-wrap">
     
        <h3 id="main2">subscribe now and get a private tutor</h3>
          </div>
      <div class="sub-wrap">
          <button id="subscribe" ><a href="#">SUBSCRIBE NOW</a></button>

      </div>
          </div>
    <h2>TOP COURSES </h2>
    <!-- Top courses -->
    <div id="card" class="card" ><img src="../assets/images/brain-color-colorful-cube-19677.jpg"
        class="card-img-top" alt="...">
      <div class="card-body">
        <h5 class="card-title">Mathematics</h5><small class="card-text">Learn all the basics of Pythagoras theorem
          <br>21/07/2020 <br>2hrs 30mins </small><br><a href="" class="btn btn-danger">Watch now</a>
      </div>
    </div>
  </div>
  </div>
</template>
<script>
  export default {}

</script>
<style scoped>
.wrap-courses{
  width: 100%;
  left: 0;
  position: relative;
  background-color: rgb(255, 255, 255);
   z-index: 48;
   padding-top:10px;
   margin-top: -50px;
   padding-bottom: 20px;
}
  h2 {
    margin-bottom: 20px;
    margin-top: 40px;
    font-family: montserrat;
    color: #2f80ed;
    text-align: center;
  }

  #card {
    clear: both;
    display: inline-block;
    margin-bottom: 20px;
    margin-right: 20px;
    margin-left: 60px;
    align-self: center;
    justify-content: center;
    width: 18rem;
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
    left: 0px;
    background: #2D9CDB;
   height: fit-content;
    padding: 20px;
  
  }
#main {
    position: relative;
    font-family: Cardo;
    font-style: normal;
    font-weight: bold;
    font-size: 38px;
    line-height: 92.69%;
    /* or 35px */
    color: #EDE9E9;
     padding:10px;
   
}
#main2 {
    position: relative;
    padding:10px;
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
    width: fit-content;
   border: none;
    background: #FFFFFF;
    padding: 20px;
}

button>a {
    font-family: Cardo;
    font-style: normal;
    font-weight: bold;
    font-size: 38px;
    line-height: 92.69%;
    /* or 35px */

    text-align: center;
     color: #2D9CDB;
  text-shadow: 0.5px 0.5px #33f,-0.5px -0.5px #33f;

}
.card-img-top{
  width: 100%; 
  height: 13rem; 
 justify-items: center;
}
 
.sub-wrap{
    display: flex;
    align-items: center;
    justify-content: center;

}
@media (max-width: 858px) {
 

#main {
    font-size: 22px;
    line-height: 30px;
    /* or 35px */
    color: #EDE9E9;
    text-align: center;
    padding: 10px;
}
 
#main2 {
    position: relative;
    width: fit-content;
    top: -15px;
    font-size: 18px;
    line-height: 20px;
     text-align: center;
    color: #383838;
  }

#subscribe{
    position: relative;
    padding:10px;
    text-align: center;
    width: fit-content;
    height: fit-content;
 
}
#subscribe a{
  font-size: 20px;
  color: #2D9CDB;
  text-shadow: 0.5px 0.5px #33f,-0.5px -0.5px #33f;
 margin-left: auto;
   
}

  #card {
  width:80%;
  margin-left: 10%;
  margin-right: 10%;
  display: block;
  }

}
</style>
