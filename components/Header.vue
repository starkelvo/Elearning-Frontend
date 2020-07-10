<template>
  <div>
    <section>
      <p class="sect">
        <span>Lorem Ipsum</span><br />
        simply dummy text of the printing and typesetting industry. Lorem Ipsum
        has been the industry's standard dummy text ever since the 1500s, when
        an unknown printer took a galley of type and scrambled it to make a type
        specimen book. <br />
        <button class="button"><a href="#">JOIN A LIVE CLASS NOW</a></button>
      </p>
      <div class="image"></div>
    </section>
  </div>
</template>

<script>
export default {};
</script>

<style scoped>
section {
  width: 40%;
  height: calc(100vh - 80px);
}
.sect {
  font-size: 18px;
  margin-left: 50px;
  margin-top: 50px;
  font-weight: lighter;
  line-height: 1.4;
}
@media (max-width: 858px) {
  p {
    width: 80%;
    background-size: 100%;
    height: calc(50vh);
    margin-top: 10px;
  }
}
span {
  font-size: 48px;
  font-weight: 900;
}
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
.image {
  background: url("../assets/images/undraw_teaching_f1cm.png") no-repeat;
  background-size: cover;
  height: calc(100vh - 180px);
  width: 50%;
  float: right;
  top: 0;
}
</style>
