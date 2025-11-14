<template>
    <div class="w-75 mx-auto container-fluid">
        <div class="row">
            <div class="col-lg-4">
                <a href="#" class="navbar-brand fw-bold fs-2" id="logo">Ashion</a>
                <div>
                    Lorem ipsum dolor sit amet consectetur adipisicing elit. Ipsa possimus provident soluta rerum deleniti molestiae ipsam eveniet, enim ad dolores!
                </div>
                <div class="d-flex flex-row justify-content-start gap-3">
                    <div style="background-color: gray;border-radius: 50%;">
                        <img style="width:40px;height: 40px;border-radius: 50%;" src="../assets/visa1.png" alt="">
                    </div>
                    <div style="background-color: gray;border-radius: 50%;">
                        <img style="width:40px;height: 40px;border-radius: 50%;" src="../assets/visa1.png" alt="">
                    </div>
                    <div style="background-color: gray;border-radius: 50%;">
                        <img style="width:40px;height: 40px;border-radius: 50%;" src="../assets/visa1.png" alt="">
                    </div>
                    <div style="background-color: gray;border-radius: 50%;">
                        <img style="width:40px;height: 40px;border-radius: 50%;" src="../assets/visa1.png" alt="">
                    </div>

                 
                </div>
            </div>
            <div class="col">
                <div class="linkHeading">Quick Links</div>
                <ul class="linksContainer">
                    <li><a href="#" class="linkItem">About</a></li>
                    <li><a href="#" class="linkItem">Blogs</a></li>
                    <li><a href="#" class="linkItem">Contact</a></li>
                    <li><a href="#" class="linkItem">FAQ</a></li>
                </ul>
            </div>
            <div class="col">
                <div class="linkHeading">Account</div>
                <ul class="linksContainer">
                    <li><a href="#" class="linkItem">My Account</a></li>
                    <li><a href="#" class="linkItem">Order Tracking</a></li>
                    <li><a href="#" class="linkItem">Checkout</a></li>
                    <li><a href="#" class="linkItem">Wishlist</a></li>
                </ul>
            </div>
            <div class="col-lg-4 d-flex flex-column justify-content-start align-items-start gap-3">
                <div class="linkHeading">Newsletter</div>
                <div id="inputBox">
                    <input type="text" placeholder="Email">
                    <button id="subscribeBtn">Subscribe</button>
                </div>
                <div class="d-flex flex-row justify-content-lg-start align-items-center gap-3">
                    <a href="#"><img style="width:40px;height: 40px;border-radius: 50%;" src="../assets/facebook.png" alt=""></a>
                    <a href="#"><img style="width:40px;height: 40px;border-radius: 50%;" src="../assets/facebook.png" alt=""></a>
                    <a href="#"><img style="width:40px;height: 40px;border-radius: 50%;" src="../assets/facebook.png" alt=""></a>
                    <a href="#"><img style="width:40px;height: 40px;border-radius: 50%;" src="../assets/facebook.png" alt=""></a>
                </div>
            </div>
        </div>
        <div id="divider"></div>
        <div id="copyright">
            Copyright 2025 
        </div>
    </div>
</template>
<script>

</script>
<style scoped>
#logo{
    font-family: "Yellowtail", cursive;
}
.linkHeading{
    font-weight: bold;
    font-size: 1.25rem;
}
.linksContainer{
    margin: 0; 
    padding: 0;
    list-style-type: none;
    display: flex;
    flex-direction: column;
    justify-content: flex-start;
    align-items: flex-start;
    gap:.25rem;
}
.linkItem{
    text-decoration: none;
    color: gray;
}
.linkItem:hover{
    color:darkgray;
}
#inputBox{
    position: relative;
    width: fit-content;
    display: inline-block;
    width: 100%;
}
#subscribeBtn{
    position: absolute;
    right: 0px;
    top: 50%;
    transform: translateY(-50%);
    cursor: pointer;
    border-radius: 1.5rem;
    font-size: 1rem; 
    border: none;
    color: white;
    padding: .5rem .75rem; 
    background-color: red;
}
input{
    border-radius: 1.5rem;
    width: 100%;
    border:1px solid lightgray; 
    font-size: 1rem;
    padding: .5rem;
    padding-left: 1rem;
}
.circle {
    border-radius: 50%;
    background-color: gray;
    display: flex;
    align-items: center;
    justify-content: center;
}

.circle img {
    width: 35px;
    height: 35px;
    object-fit: cover;
}
#divider{
margin-top: 4rem;
background-color: lightgray;
width: 100%;
height: 1px;
}
#copyright{
    text-align: center;
    margin-top: .5rem;
}
</style>