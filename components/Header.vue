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
section {
  width: 100%;
  display: inline-flex;
  justify-items: center;
  justify-content: center;

}

@media (max-width: 858px) {
  section {
    width: 100%;
    display: flexbox;
    flex-wrap: wrap-reverse;
    justify-items: center;
    justify-content: center;
  }
}
/* Header writeup style */
.sect {
  width: 40%;
  height: calc(100vh - 80px);
  font-size: 18px;
  padding-left: 50px;
  padding-top: 50px;
  font-weight: lighter;
  line-height: 1.4;
}
@media (max-width: 858px) {
  .sect {
    width: 100%;
    background-size: 100%;
    height: calc(50vh);
    margin-top: 10px;
    display: block;
  }
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
@media (max-width: 858px) {
  .image {
    background-size: cover;
    height: calc(100vh - 180px);
    width: 100%;
    margin-right: 20px;
  }
}
/* Horizontal line */
hr {
  border-color: #2f80ed;
}
</style>
