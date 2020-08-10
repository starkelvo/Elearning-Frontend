<template>
     <div class="card">
       <div class="top-card">
           <h3>Wrong password!</h3>
       </div>
       <div class="mid-card">
           <p class="red-text">the password you entered does not match this account. Please enter correct password.</p>
       <input type="text" placeholder="email address or mobile no" class="code-input">
        <input type="password" placeholder="password" class="code-input">
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