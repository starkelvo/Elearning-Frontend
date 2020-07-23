<template>
    <div>
      
      <div class="container">
         <ChangePic class="profile"/>
       <div class="settings">
        <div class="pass">user name</div>
        <div class="pass">email</div>
      <div class="pass">phone no</div>
      <div class="pass">choose subjects</div>
      <div class="pass">change password</div>
      <div class="pass">subscription</div>
      <div class="pass">log out</div>
        <div class="pass">deactivate account</div>
        </div>
    
      </div>
    </div>
</template>

<script>
export default {
    
}
</script>

<style scoped>
.container{
  display: grid;
  grid-template-columns: 1fr 1fr;
}
.pass{
   font-weight: lighter;
  width: 100%;
  height: 10%;
  font-size: 30px;
  color: rgb(61, 59, 59);
  display: flex;
 text-align: left;
  padding-left: 20px;
  text-shadow:inset 0.5px 0.5px #003,inset -0.5px -0.5px #003;
  border: 0.3px solid rgba(123, 123, 124, 0.274);
}
.pass:hover{
    background-color: rgba(207, 210, 211, 0.342);

}

@media (max-width: 858px) {
  .settings, .container{
display:block;
  }
  .settings{
    margin: 10%;
    width: 80%; 
  }
  .pass{
    font-size: 22px;
    padding: 10px;
  }
}
</style>