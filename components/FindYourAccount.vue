<template>
     <div class="card">
       <div class="top-card">
           <h3>Find your account</h3>
       </div>
       <div class="mid-card">
           
        <p>Please enter your email address or phone number to search for your account </p>
       <input type="text" placeholder="email address or mobile no" class="code-input">
        <div class="card-btns">
                 <nuxt-link to="/requestPasswordCode" >  
                  <button class="continue">Search</button>
                 </nuxt-link>
                  <nuxt-link to="/" >  
                <button class="not">Cancel</button>
                  </nuxt-link>
            </div>
        </div>
        <div class="bottom-card">
           
               <div class="noAcc">
                 <p>Don't have an account with us? 
                    <nuxt-link to="/signup"> <button class="not">Sign up</button> </nuxt-link>
                     </p>
                   
            </div>
        </div>

       
           </div>
</template>