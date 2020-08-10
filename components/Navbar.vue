<template>
  <div>
    <nav>
      <input type="checkbox" name="" id="check" />
      <label for="check" class="checkbtn">
        <!-- <i class="fas fa-bars"></i> -->
        <font-awesome-icon :icon="['fas', 'bars']"/>
      </label>
      <label for="logo" class="logo">E-LOGO</label>
      <ul>
        <li><nuxt-link class="" to="/">Home</nuxt-link></li>
        <li><nuxt-link to="/contact">Contact</nuxt-link></li>
        <li><nuxt-link to="/about">About</nuxt-link></li>
        <li><nuxt-link class="active" to="/user">Live Class</nuxt-link></li>
        <li><nuxt-link class="login" to="/login">login</nuxt-link></li>
        <li><nuxt-link class="signup" to="/signup">Signup</nuxt-link></li>
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
  z-index: 200;
  position: relative;
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
    width: 0%;
    height: 0vh;
    top: 80px;
    left: 300%;
    text-align: center;
    transition: all 0.5s;
    background: #19173f48;
  }
  nav ul li {
    display: block;
    width: 50%;
    margin:  0;
    padding: 20px;
    line-height: 30px;
    background: #6a62fdc7;
    border-bottom: 1px solid #6b62fd;
    margin-left: 100%;
    transition: all 1s;
  
  }
   nav ul li:hover{
       background: #29283b;
  
   }
  nav ul li a {
    font-size: 20px;
    font-weight: bold;
    color: white;
   text-shadow: 0.5px 0.5px tomato,-0.5px -0.5px tomato;
 
  }
  a:hover,
  a.active {
    background: none;
    color: cyan;
  }
  #check:checked ~ ul {
    left: 0%;
     width: 100%;
    height: 100vh;
   
  }
  #check:checked ~ ul li:nth-child(odd){
   animation: li 0.7s linear both;
 animation-delay: 0.5s;
 
  }
  #check:checked ~ ul li:nth-child(even){
   animation-delay: 0.5s;
 animation: li 0.6s linear both;

  }
   
  @keyframes li {
    0%{
      margin-left: 100%;  
      padding: 0px;
    line-height: 0px;
    border-radius: 50%;
    }
    100%{
      margin-left: 50%;
      padding: 20px;
    line-height: 30px;
     border-radius: 0 0 0 0;
 
     }
  }
}
</style>
