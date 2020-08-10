<template>
     <div class="card">
       <div class="top-card">
           <h3>Enter Security Code</h3>
       </div>
       <div class="mid-card">
            <p>We sent your code to 08077754537</p>         
            

        <p>please check your email/phone for a message with your code </p>
       <input type="text" placeholder="Enter Security Code" class="code-input">
          <div class="card-btns">
                <nuxt-link to="/changePassword" >  
                <button class="continue">   Continue</button> 
                </nuxt-link>
                 <nuxt-link to="/" >  
                <button class="not">Cancel</button>
                 </nuxt-link>
            </div>
        </div>
        <div class="bottom-card">
             <nuxt-link to="/findYourAccount" >  
            <p>Didn't get a code? 
                 <nuxt-link to="/FindYourAccount" >  
                <button class="continue">Click here</button> 
                </nuxt-link>
            </p>
             </nuxt-link>
         
        </div>

       
           </div>
</template>