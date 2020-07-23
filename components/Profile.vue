<template>
    <div>
        <main>
           <div class="profile">
              <div class="image " > 
              <img src="../assets/images/jzee.jpg" class="image1" alt="profile pic">
              <div class="image2"></div> 
              </div>
          
            <div class="pro2">
              <ul>
                <li class="name"><a href="">John Doe</a></li>
                <li class="edit"><nuxt-link to="/editProfile">Edit Profile</nuxt-link></li>
       
              </ul>
            </div>
                        </div>
          
        </main>
    </div>
</template>

<script>
export default {
    
}
</script>

<style scoped>
*{
  margin:0;
  padding: 0;
  box-sizing: border-box;
}
main {
    display: inline-flex;
    position: relative;
}
.profile {
    position: relative;
    display: block;
    list-style: none;
    line-height: 50px;
    /* border: 1px solid gray; */
      /* box-shadow: inset 2px 2px 10px #003, 0 0 5px #003,inset -2px -2px 10px #003, 0 0 5px #003; */
    width: 20vw;
    height: 100vh;
    margin-left: 2em;
    font-weight: 700;
    font-size: large;
}
li{
  text-align: center;
  display: block;
}
.image{
  width:100%;
  height: 40%;
  /* margin-top:20px;
  margin-left:10%; */
  box-shadow: inset 2px 2px 10px #003, 0 0 5px #003,inset -2px -2px 10px #003, 0 0 5px #003;
    border-radius: 50%;

}
.image1{
   width:100%;
  height: 100%;
  margin-top:0;
  margin-left: 0;
   border-radius: 50%;

}
.image2{
  position: absolute;
  left: 0;
  top:0;
  height: 40%;
  width: 100%;
  box-shadow: inset 2px 2px 10px #003, 0 0 5px #003,inset -2px -2px 10px #003, 0 0 5px #003;
 background-color: rgba(72, 180, 230, 0.089);
  border-radius: 50%;

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
  .edit{
    padding: 10px;
    border-radius: 20px;
    background-color:#007bff;
   }
  .edit a{
  color: white;
 
  } 
   @media (max-width: 952px) {
   *{
  margin:0;
  padding: 0;
  box-sizing: border-box;
}
main {
    display: block;
}
.profile { 
  line-height: 50px;
  width: 94vw;
  height: 20vh;
  font-weight: 700;
  font-size: 15px;
  margin-left: 2vw;
}

li{
  text-align: center;
  display: inline-block;
}
.image{
  width:30%;
  height: 100%;
  }

.image2{
  height: 100%;
  width: 30%;
 }
 .pro2{
   position: absolute;
   height: 100%;
   width: 65%;
   left: 35%;
   top: 0;
 }
 .edit{
   width: 80%;
  margin-left: 0%;
  display: block;
 }
 .course-desc{
    width: 96vw;
    margin-top: 0vh;
    display: block;
    position: relative;
    margin-left: 0;
  } 
 #image {
    position: relative;
    width: 80%;
    height: 40%;
    left: 10%;
    top: 50px;
    display: block;
  }

 .des {
  font-family: Roboto;
  margin-left: 10%;
  margin-top: 2%;
  width: 80%;
  position: relative;
  display: block;
  }
  
  .title {
    font-weight: 600;
    font-size: 20px;
  }
/* Description style */
  .title-desc {
    font-size: 16px;
  }
  .btn-danger {
    position: relative;
    width: 80%;
    height: 7%;
    left: 10%;
    top: 10%;
    margin-top: 10%;
    font-size: 25px;
    line-height: 30px;
    display: block;
    padding: 10px 0;
    box-sizing: border-box;
   }
  }
</style>