<template>
    <div class="card">
       <div class="top-card">
           <h3>Reset Your Password</h3>
       </div>
       <div class="mid-card">
            <p>How do you want to receive the code to reset your password?</p>         
            

        <p> Send code via SMS?</p>
        <p>08077754537</p>
        <nuxt-link to="/ChangePassword">
            <button class="continue">continue</button>
        </nuxt-link>    
        </div>
        <div class="bottom-card">
            <p>no longer have access to this?</p>
            <div class="card-btns">
                <nuxt-link to="/FindYourAccount">
                <button class="not">Not you?</button>
                </nuxt-link>
            </div>
        </div>

       
           </div>
</template>
<script>
export default {
    
}
</script>
<style  scoped>

</style>