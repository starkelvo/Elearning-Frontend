<template>
    <div>
        <section>
          <div class="course-desc">
          <!-- Course Image card -->
            <img src="../assets/images/brain-color-colorful-cube-19677.jpg"
        class="card-img-top" id="image" style="justify-item: center;" alt="...">
        <a href="" class="btn btn-danger">Watch now</a>
        <!-- Course description -->
        <div class="des">
          <span class="title">Mathematics</span><br> <small class="title-desc">Learn all the basics of Pythagoras theorem
          <br>21/07/2020 <br>2hrs 30mins  <br> <span style="color: red">Executive class</span></small>
        </div>
        </div>
        </section>
        <hr>
        <div class="what">
          <h5>What you will learn</h5>
        </div>
    </div>
</template>

<script>
export default {
    
}
</script>

<style scoped>

.des {
  font-family: Roboto;
  width: 40%;
  margin-bottom: 10em;
  margin-left: 40%;
  margin-top: -12em;
}
.title{
  font-weight: 600;
  font-size: xx-large;
}
.title-desc {
  font-size: x-large;
}
#image{
    position: relative;
    width: 65vh;
    height: 30%;
    left: 5em;
    top: 5em;
}
@media (max-width: 952px) {
  #image {
    position: relative;
    width: 65vh;
    height: 100%;
    left: 4em;
    top: 5em;
  }
}
.btn-danger{
position: relative;
width: 65vh;
height: 7%;
left: 2.5em;
top: 2.8em;
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
hr {
  
  border-color: #2f80ed;
}
.what {
  position: relative;
  width: 70%;
  border: 1px solid black;
  border-radius: 8px;
  left: 10em;
  
}
</style>