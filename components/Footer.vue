<template>
    <div class="footer">
        <label for="logo" class="logo">E-LOGO</label><br>
        <div class="links">
        <ul>
            <li><a href="#">About us</a></li>
            <li><a href="#">Contact us</a></li>
            <li><a href="#">Live Classes</a></li>
        </ul>
        <ul>
            <li><a href="#">Help</a></li>
            <li><a href="#">Support</a></li>
            <li><a href="#">Affiliate</a></li>
            <li><a href="#">Terms & Conditions</a></li>
        </ul>
        <ul>
            <li><a href="#">Featured courses</a></li>
            <li><a href="#">Blog</a></li>
        </ul>
        </div>
    </div>
</template>

<script>
export default {
    
}
</script>

<style scoped>
.footer {
    position: absolute;
    width: 100%;
    height: 306px;
    left: 0px;
    background: linear-gradient(180deg, rgba(107, 98, 253, 0.43) 0%, rgba(196, 196, 196, 0.31) 100%);
    }
label.logo {
  color: #6b62fd;
  font-size: 35px;
  font-family: montserrat;
  line-height: 80px;
  padding: 0 100px;
  font-weight: bold;
}
ul {
  margin-right: 100px;
}
ul li {
  display: block;
  line-height: 30px;
}
ul li a {
    position: relative;
    left: 143px;

    font-family: Roboto;
    font-style: normal;
    font-weight: normal;
    font-size: 16px;
    /* or 25px */


    color: #494949;
}
.links{
    display: inline-flex;
}

@media (max-width: 858px) {

.links{
    display: block;
}
.footer {
    height: fit-content;
    background: linear-gradient(180deg, rgba(107, 98, 253) 0%, rgba(196, 196, 196) 100%);
    }
label.logo {
  color: #3b3a58;
}
ul {
 display:block;
 justify-content: center;
 align-items: center;
}
}
</style>