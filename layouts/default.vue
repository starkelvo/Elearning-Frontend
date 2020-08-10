<template>
  <div>
    <Navbar />
    <Nuxt />
    <Footer />
  </div>
</template>

<style>
.card{
    width: 60%;
    margin: 3% auto;
    box-shadow: 0 0 5px grey;
    padding: 20px;
    color:#6b62fd;
}
.top-card  {
    padding: 10px;
    text-align: center;
    border-bottom: 1px dotted grey;

}
.mid-card  {
    padding: 20px 0;
    border-bottom: 1px dotted grey;

}

.bottom-card{
  padding: 10px 0;
  display: flex;
  justify-content: space-between;
  background-color: #ffffee;
}
.not, .continue{
    padding:10px;
    font-weight: 800;
    margin-right: 10px;
    border-radius: 10px;
    color: #6B62FD;
    background: white;
    border: none;
    box-shadow:0 0 5px #6B62FD;
    transition: ease 0.5s;
}
.continue{
     background: #6b62fd;
    color: white;
   }
.continue:hover{
     background: #29283b;
}
.code-input{
  /* width: 60%; */
  padding: 5px;
  border: 1px dotted grey;
  border-radius: 10px;
   width: 90%;
  margin: 20px 0;
}
.code-input:active{
   border: 1px dotted grey;
}

.red-text{
  color: red;
  background-color: rgb(247, 230, 236);
  padding: 7px;
}

@media (max-width: 858px) {
  
.card{
    width: 90%;
    margin: 10% auto;
}

.code-input{
  width: 90%;
  margin: 20px 0;
  
}
}
</style>
