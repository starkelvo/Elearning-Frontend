<template>
  <div>
    <nav>
      <input type="checkbox" name="" id="check" />
      <label for="check" class="checkbtn">
        <i class="fas fa-bars"></i>
      </label>
      <label for="logo" class="logo">E-LOGO</label>
      <ul>
        <li><a class="" href="#">Home</a></li>
        <li><a href="#">Contact</a></li>
        <li><a href="#">About</a></li>
        <li><a class="active" href="#">Live Class</a></li>
        <li><a class="login" href="#">login</a></li>
        <li><a class="signup" href="#">Signup</a></li>
      </ul>
    </nav>
  </div>
</template>

<script>
export default {};
</script>

<style scoped>
@import url("https://fonts.googleapis.com/css?family=Roboto+Condensed");

nav {
  height: 80%;
  width: 100%;
}
label.logo {
  color: #6b62fd;
  font-size: 35px;
  font-family: montserrat;
  line-height: 80px;
  padding: 0 100px;
  font-weight: bold;
}
nav ul {
  float: right;
  margin-right: 100px;
}
nav ul li {
  display: inline-block;
  line-height: 80px;
  margin: 0 5px;
}
nav ul li a {
  color: #000000;
  font-size: 17px;
  padding: 7px 13px;
  border-radius: 50px;
  font-weight: 400;
}
a.active,
a:hover {
  background: #f42525;
  transition: 0.5s;
  color: white;
}
a.signup,
a:hover {
  color: white;
  background: #6b62fd;
  transition: 0.5s;
}
a.login,
a:hover {
  border: 1px solid #6b62fd;
  transition: 0.5s;
}
.checkbtn {
  font-size: 30px;
  color: #6b62fd;
  float: right;
  line-height: 80px;
  margin-right: 40px;
  cursor: pointer;
  display: none;
}
#check {
  display: none;
}
@media (max-width: 952px) {
  label.logo {
    font-size: 30px;
    padding-left: 50px;
  }
  nav ul li a {
    font-size: 16px;
  }
}
@media (max-width: 858px) {
  .checkbtn {
    display: block;
  }
  ul {
    position: fixed;
    width: 100%;
    height: 100vh;
    background: #6b62fd;
    top: 80px;
    left: -100%;
    text-align: center;
    transition: all 0.5s;
  }
  nav ul li {
    display: block;
    margin: 50px 0;
    line-height: 30px;
  }
  nav ul li a {
    font-size: 20px;
  }
  a:hover,
  a.active {
    background: none;
    color: cyan;
  }
  #check:checked ~ ul {
    left: 0;
  }
}
</style>
