<template>
  <div>
    <div class="container">
        <div class="phone sub">call</div>
        <div class="email sub">email</div>
        <div class="msg sub">message</div>
        <div class="twit sub">twitter</div>
        <div class="face sub">facebook</div>
        <div class="circle">contact us</div>
    </div>
  </div>
</template>

<script>
export default {
    
    };
</script>

<style scoped>
*{
    margin:0;
    padding: 0;
    box-sizing: border-box;
}
/* body{
    background: darkcyan;
} */
 .container{
     position: relative;
     padding: 20px;
    height: 100vh;
     width: 100vw;
  
 }
 .sub{
      height: 70px;
     width: 70px;
     left:0;
     top:0;
     background-color: #6b62fd;
     border-radius: 100%;
     display: flex;
     align-items: center;
     justify-items: center;
     text-align:center;
     color: rgb(255, 255, 255);
    text-shadow: 1px 1px rgb(2, 2, 80),-1px -1px rgb(2, 2, 80);
     font-weight: 600;
     box-shadow: 0 0 5px rgb(197, 237, 250),inset 0 0 5px rgb(5, 5, 22);
     position: absolute;
     word-break: break-all;
 }
 .phone{
      left:230px;
     top:50px;
     animation: phone 6s infinite;
   }
 
 .email{
      left:400px;
     top:150px;
   animation: email 6s infinite;
 }
 .msg{
      left:330px;
     top:350px;
   animation: msg 6s infinite;
 }
 .twit{
      left:50px;
     top:150px;
  animation: twit 6s infinite;
  }
 .face{
      left:100px;
     top:350px;
  animation: face 6s infinite;
  }
 
 .circle{
     position: absolute;
      height: 100px;
     width: 100px;
     background-color: #6b62fd;
     border-radius: 100%;
     top: 200px;
     left: 200px;
    box-shadow: 0 0 5px rgb(197, 237, 250),inset 0 0 5px rgb(5, 5, 22);
  display: flex;
     align-items: center;
     justify-items: center;
     text-align:center;
     color: rgb(255, 255, 255);
    text-shadow: 1px 1px rgb(2, 2, 80),-1px -1px rgb(2, 2, 80);
     font-weight: 600;
    
 }
 @keyframes phone{
     0%,30%{
          left:230px;
     top:50px; 
     }
     20%{
            left:220px;
     top:220px;  
     }
 }
@keyframes face{
     0%,30%{
          left:100px;
     top:350px; 
     }
     20%{
            left:220px;
     top:220px;  
     }
 }

 @keyframes twit{
     0%,30%{
          left:50px;
     top:150px; 
     }
     20%{
            left:220px;
     top:220px;  
     }
 }

 @keyframes msg{
     0%,30%{
          left:330px;
     top:350px; 
     }
     20%{
            left:220px;
     top:220px;  
     }
 }

 @keyframes email{
     0%,30%{
          left:400px;
     top:150px; 
     }
     20%{
            left:220px;
     top:220px;  
     }
 }
  @media (max-width: 952px) {
  
 .sub{
      height: 70px;
     width: 70px;
   }
 .phone{
      left:140px;
     top:50px;
     animation: phone 6s infinite;
   }
 
 .email{
      left:280px;
     top:150px;
    animation: email 6s infinite;
 }
 .msg{
      left:250px;
     top:320px;
   animation: msg 6s infinite;
 }
 .twit{
      left:5px;
     top:150px;
  animation: twit 6s infinite;
  }
 .face{
      left:60px;
     top:320px;
  animation: face 6s infinite;
  }
 
 .circle{
      height: 100px;
     width: 100px;
     top: 170px;
     left: 120px;
     
 }
 @keyframes phone{
     0%,30%{
        left:140px;
     top:50px;
     }
     20%{
            left:130px;
     top:180px;  
     }
 }
@keyframes face{
     0%,30%{
           left:60px;
     top:320px; 
     }
     20%{
            left:130px;
     top:180px;  
     }
 }

 @keyframes twit{
     0%,30%{
          left:5px;
     top:150px;
     }
    20%{
            left:130px;
     top:180px;  
     }
 }

 @keyframes msg{
     0%,30%{
         left:250px;
     top:320px;
     }
     20%{
            left:130px;
     top:180px;  
     }
 }

 @keyframes email{
     0%,30%{
        left:280px;
     top:150px;
     }
     20%{
            left:130px;
     top:180px;  
     }
 }
 
  
  
  }



</style>
