<template>
  <div>
    <!-- Header container (Section) -->
    <section>
      <!-- Header writeup -->
      <div class="sect">
        <span>Lorem Ipsum</span><br />
        simply dummy text of the printing and typesetting industry. Lorem Ipsum
        has been the industry's standard dummy text ever since the 1500s, when
        an unknown printer took a galley of type and scrambled it to make a type
        specimen book. <br />
        <button class="button"><a href="#">JOIN A LIVE CLASS NOW</a></button>
      </div>
      <!-- Header Image -->
      <div class="image"></div>
    </section>
    <hr>
  </div>
</template>

<script>
export default {};
</script>

<style scoped>
/* Header Container Style */
*{
  margin: 0;
  padding: 0;
  box-sizing: border-box;
}
section {
  width: 100%;
  display: inline-flex;
  justify-items: center;
  justify-content: center;
  background-color: white;
}

/* Header writeup style */
.sect {
  width: 40%;
  /* height: calc(100vh - 80px); */
  font-size: 18px;
  padding-left: 50px;
  padding-top: 50px;
  font-weight: lighter;
  line-height: 1.4;
   background-color: white;
 
}

span {
  font-size: 48px;
  font-weight: 900;
}
/* Button */
.button {
  background-color: #f42525; /* Green */
  border: none;
  color: white;
  padding: 15px 32px;
  margin: 15px 42px;
  border: none;
  border-radius: 50px;
  width: 80%;
  text-align: center;
  text-decoration: none;
  display: inline-block;
  font-size: 16px;
  box-shadow: 0 0 5px rgb(83, 16, 16), inset 2px 2px 10px rgb(85, 3, 3);
  transition: all ease 0.5s;
}
.button:hover{
  box-shadow: none;
}
a {
  color: white;
}
/* Header image */
.image {
  background: url("../assets/images/undraw_teaching_f1cm.png") no-repeat;
  background-size: cover;
  height: calc(100vh - 180px);
  width: 40%;
  margin-right: 20px;
}
/* Horizontal line */
hr {
  border-color: #2f80ed;
}

@media (max-width: 858px) {
 
    .image {
    background-size: 100% 100%;
    height: 50vh;
    width: 100%;
    margin-left: 0;
    position: fixed;
  }
  .sect {
    position: relative;
    width: 100%;
    background-size: 100%;
    /* height: calc(50vh); */
    margin-top: 51vh;
    display: block;
    background-color: rgb(255, 255, 255);
    z-index: 50;
 padding: 50px;

  }
}
</style>
