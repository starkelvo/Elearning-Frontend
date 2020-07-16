<template>
    <div>
        <main>
            <ul>
                <li><a href="">John Doe</a></li>
                <li><a href="">Change Profile Picture</a></li>
                <li><a href="">Notification</a></li>
                <li><a href="">Change password</a></li>
                <li><a href="">Edit Profile</a></li>
            </ul>
            <div class="course-desc">
        <!-- Course Image card -->
        <img src="../assets/images/brain-color-colorful-cube-19677.jpg" class="card-img-top" id="image"
          style="justify-item: center;" alt="...">
        <a href="" class="btn btn-danger">Watch now</a>
        <!-- Course description -->
        <div class="des">
          <span class="title">Mathematics</span><br> <small class="title-desc">Learn all the basics of Pythagoras
            theorem
            <br>21/07/2020 <br>2hrs 30mins <br> <span style="color: red">Executive class</span></small>
        </div>
      <hr>
      </div>
        </main>
    </div>
</template>

<script>
export default {
    
}
</script>

<style scoped>
main {
    display: inline-flex;
    position: relative;
}
ul {
    position: relative;
    display: block;
    list-style: none;
    line-height: 50px;
    border: 1px solid gray;
    width: 20vw;
    height: 100vh;
    margin-left: 2em;
    font-weight: 700;
    font-size: large;
}
.course-desc {
    margin-left: 3em;
}
 .des {
    font-family: Roboto;
    
    margin-left: 70%;
    margin-top: -9em;
  }
  /* Descriptio title style */
  .title {
    font-weight: 600;
    font-size: x-large;
  }
/* Description style */
  .title-desc {
    font-size: large;
  }
/* Main image */
  #image {
    position: relative;
    width: 45vh;
    height: 40%;
    left: 5em;
    top: 3.6em;
  }
/* Main Image responsiveness */
  @media (max-width: 952px) {
    #image {
      position: relative;
      width: 35vh;
      height: 100%;
      left: 4em;
      top: 5em;
    }
  }
/* Watch now button style */
  .btn-danger {
    position: relative;
    width: 45vh;
    height: 7%;
    left: -6.6em;
    top: 6.9em;
    justify-items: center;
    background: #F45E3D;
    border-radius: 8px;
    font-family: Roboto;
    font-style: normal;
    font-weight: 500;
    font-size: 32px;
    line-height: 125.69%;
    /* or 40px */
    color: #FFFFFF;
    border: none;
  }
</style>