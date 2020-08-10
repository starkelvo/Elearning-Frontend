<template>
<div id="body">
    <div id="about-container">
       <b-img class="image1" center src="https://empoweredtech.usc.edu/wp-content/uploads/2017/08/em-2-945x350.jpg" 
       alt="Center image"></b-img>
    
    <div id="content" >
    <h1>About Us</h1>
    <p>
        Tutorsng is a revolutionary E-learning platform in Africa. We leverage the best in class teachers and technology solutions to create high-quality, affordable, and accessible education for African students. We have built a platform that helps African students be the very best they can be - an app that allows them to maximize their academic achievement and prepare for a future in various disciplines and subjects. Our team of passionate and talented people has together built a learning experience unprecedented in richness, scope, interactivity, and effectiveness.
    </p>
  </div>
    </div>
</div>
</template>

<script>
export default {
    
}
</script>

<style scoped>

*{
    margin:0;
    padding:0;
    box-sizing: border-box;
}
body{
    background: #F2F2F2
}
.nav{
    position: absolute;
width: 100%;
height: 5%;
left: 0px;
top: 0px;
background: linear-gradient(180deg, rgba(203, 200, 200, 0.5) 0%, rgba(196, 196, 196, 0) 100%);
z-index: 100;
}
#content{
margin-top: 5%;
}
#about-container{
    width:70%;
    position: relative;
    left: 15%;
  
}
.image1{
    width: 100%;
    left: 0;
    height: 50vh;
}
@media (max-width: 858px) {

.image1{
    width: 100%;
    left: 0;
    height: 40vh;
}
}
</style>