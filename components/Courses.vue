<template>
    <div>
        <h2>
            COURSES
        </h2>
        <div id="card" class="card" style="width: 18rem;">
  <img src="../assets/images/brain-color-colorful-cube-19677.jpg" class="card-img-top" style="width: 18rem; height: 13rem; justify-item: center;" alt="...">
  <div class="card-body">
    <h5 class="card-title">Mathematics</h5>
    <small class="card-text">Learn all the basics of Pythagoras theorem <br>
        21/07/2020 <br>
        2hrs 30mins
    </small><br>
    <a href="" class="btn btn-danger">Watch now</a>
  </div>
</div>
    </div>
</template>

<script>
export default {
    
}
</script>

<style scoped>
h2 {
    padding-left: 60px;
    font-family: montserrat;
    color: #2f80ed;
}

#card{
    clear:both;
    display: inline-block;
    margin-bottom: 20px;
    margin-right: 20px;
    margin-left: 60px;
    align-self: center;
    justify-content: center;
    
}
#card:hover{
  -webkit-transform: scale(1.05);
        -ms-transform: scale(1.05);
        transform: scale(1.05);
        transition: ease-in 0.3s;
}
</style>