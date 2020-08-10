<template>
     <div class="card">
       <div class="top-card">
           <h3>Account not found!</h3>
       </div>
       <div class="mid-card">
           <p class="red-text">We could not find any account with your address. Please, enter your phone number or email address</p>
       <input type="text" placeholder="email address or mobile no" class="code-input">
        <div class="card-btns">
            <nuxt-link to="/login">
                <button class="continue">log in</button>
            </nuxt-link>
                  </div>
        </div>
        <div class="bottom-card">
            
            <div class="noAcc">
                 <p>Don't have an account with us? 
                     <nuxt-link to="/signup">
                     <button class="not">Sign up</button>
                     </nuxt-link>
                     </p>
                
            </div>
           
        </div>

       
           </div>
</template>
<style scoped >
.card-btns{
    display: block;
}
.noAcc{
    display: flex;
    display: block;
}
.not{
    margin-left: 20px;
}
.continue{
    float: right;
}
</style>