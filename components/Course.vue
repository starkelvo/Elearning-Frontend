<template>
  <div>
    <section>
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
      </div>
    </section>
    <hr>
    <!-- What you'll learn part -->
    <div class="what">
      <h5>What you will learn</h5>
      <ul>
        <li>- You have used the node ecosystem (npm, Express, etc.). This is NOT an intro to node class and I will NOT
          cover these in detail. <br>

          <br>- You have basic command line knowledge (at least capable of navigating and running a program)</li>

        <li>- You have a solid working knowledge of JavaScript and nodejs (Not a ninja, but you are not new).

          You have a computer capable of running Nodejs.</li>
      </ul>
    </div>
    <!-- Requirement part -->
    <div class="requirement my-5">
      <h5>Requirements</h5>
      <p>Basic Programming <br>
        Javascript Basics <br>
        HTML & CSS</p>
      <h5>What this course is about?</h5>
      <p>Learn Vue.js and Node.js by building an Amazon Clone. The course will guide you to build the website step by
        step. We will go through the fundamentals of building basic API up to building a complicated Frontend!

        The course is unique in terms of the design because it is using the same design from Amazon. The course is aimed
        at people who know basic programming, especially in Javascript because that is the main language that the course
        is using.

        Javascript is the main language for modern web applications like Airbnb, Discord, Youtube Netflix and many more
        (to be honest every single website uses Javascript :)) Writing it in JQUERY would be overwhelming because of the
        spaghetti code that you’ll end up with.

        By using modern Javascript frameworks like Vue.js and Nuxt.js, it would help in terms of code management,
        development speed and the user experience of the Website. Your future website (Mark my word, you will have one
        soon) will feel like an app if using modern frameworks, smooth navigation between different pages and better
        experience, in return visitors of your website, will stay uses your app longer :)</p>

        <!-- Comments Start here -->
      <h6>Comments</h6>
      <input type="text"> <br>
      <button class="btn btn-primary">SEND</button>
    </div>
    <div class="comments">
      <img src="../assets/images/brain-color-colorful-cube-19677.jpg" alt=""> <br>
      <span>John Doe <br>1 month ago <br>That's awesome. The instructor really knows what he's doing. He writes the code
        very quickly and accurately and explains everything what he is typing. And there is git link of final code wich
        is really amazing.</span>
    </div>
  </div>
</template>

<script>
  export default {

  }

</script>

<style scoped>
/* Description style */
  .des {
    font-family: Roboto;
    width: 40%;
    margin-bottom: 10em;
    margin-left: 40%;
    margin-top: -12em;
  }
  /* Descriptio title style */
  .title {
    font-weight: 600;
    font-size: xx-large;
  }
/* Description style */
  .title-desc {
    font-size: x-large;
  }
/* Main image */
  #image {
    position: relative;
    width: 30vw;
    height: 30%;
    left: 5em;
    top: 5em;
  }
/* Main Image responsiveness */
 
/* Watch now button style */
  .btn-danger {
    position: relative;
    width: 30vw;
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
/* Horizontal line */
  hr {
    border-color: #2f80ed;
  }
/* What you want to learn text style */
  .what {
    position: relative;
    width: 70%;
    border: 1px solid black;
    border-radius: 8px;
    left: 10em;

  }
/* List of What you want to learn */
  li {
    position: relative;
    width: 427px;
    height: 157px;
    left: 1em;
    padding-top: 1em;
    display: inline-flex;
    font-family: Roboto;
    font-style: normal;
    font-weight: 300;
    font-size: 20px;
    line-height: 100.69%;
    /* or 19px */

    list-style-type: disc;
    color: #000000;
  }
/*  */
  h5 {
    position: relative;
    display: inline-flex;
    left: 2.3em;
    font-weight: 700;
  }

  .comments>img {
    width: 5%;
    height: 10%;
    border-radius: 50px;

  }
.requirement, .comments {
  position: relative;
  width: 63%;
  left: 10em;
}
.comments {
  position: relative;
  width: 63%;
  left: 10em;
}
input {
  height: 12vh;
  border-radius: 8px solid gray;
  margin-bottom: 2px;
}
 @media (max-width: 952px) {
   
input {
  height: 12vh;
  width: 80vw;
  left: 10%;
  border-radius: 8px solid gray;
  margin-bottom: 7px;
}
  #image {
    position: relative;
    width: 80vw;
    height: 30%;
    left: 10%;
    top: 2em;
  }
    .btn-danger {
    width: 80vw;
    height: 7%;
    left: 10%;
    top: 1.8em;
  }
  .des {
    width: 100%;
    margin-bottom: 2em;
    margin-left: 0%;
    margin-top: 60px;
    display:block ;
    padding: 5% 10%;
    width: fit-content;
   }
  /* Descriptio title style */
  .title {
    font-weight: 600;
    font-size: 25px;
    text-align: center;
  }
   .title-desc {
    font-size: 20px;
  }
   .what {
    position: relative;
    width: 80%;
     border-radius: 8px;
    left: 10%;
    box-shadow: 0 0 5px rgb(71, 71, 71);
    padding: 3px;

  }
   li {
     width:100% ;
    height: fit-content ;
    left: 0;
    padding-top: 5px;
   font-size: 15px;
    line-height: 16px;
    /* or 19px */

    list-style-type: disc;
    color: #000000;
  }
  
.requirement, .comments {
  position: relative;
  width: 100%;
  left: 0;
  padding: 0 10%;
}
.comments{
  margin-bottom: 30px;
}
  }
</style>
