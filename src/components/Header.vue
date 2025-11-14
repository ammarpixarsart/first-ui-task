<template>
    <nav class="navbar navbar-expand-lg ">
        <div class="container-fluid d-flex flex-row align-items-center justify-content-around">
            <a href="#" class="navbar-brand fw-bold fs-2" id="logo">Ashion</a>
        <ul class="navbar-nav">
            <li class="nav-item activeItem"><a href="#" class="nav-link">Home</a></li>
            <li class="nav-item"><a href="#" class="nav-link">Women's</a></li>
            <li class="nav-item"><a href="#" class="nav-link">Men's</a></li>
              <li class="nav-item"><a href="" class="nav-link">Shop</a></li>
              <li class="nav-item"><a href="" class="nav-link">Pages</a></li>
              <li class="nav-item"><a href="" class="nav-link">Blog</a></li>
              <li class="nav-item"><a href="" class="nav-link">Contact</a></li>
        </ul>
        <div class="d-flex flex-row align-items-center justify-content-evenly gap-3">
            <ul class="breadcrumb">
                <li class="breadcrumb-item mt-2"><a href="#" class="text-decoration-none fw-light breadcrumbLink">Login</a></li>
                <li class="breadcrumb-item mt-2"><a href="#" class="text-decoration-none fw-light breadcrumbLink">Register</a></li>
            </ul>
                <FontAwesomeIcon :icon="['fas', 'magnifying-glass']" size="lg"/>
                <FontAwesomeIcon :icon="['far', 'heart']" size="lg"/>
               <FontAwesomeIcon :icon="faCartShopping" size="lg"/>

        </div>
         </div>
    </nav>
</template>
<style>
#logo{
    font-family: "Yellowtail", cursive;
}
.activeItem{
    border-bottom: 2px solid orange;
}
.breadcrumbLink{
    color:gray;
}

</style>
<script>
import { FontAwesomeIcon } from '@fortawesome/vue-fontawesome'
// solid icons
import { faMagnifyingGlass, faBagShopping,faCartShopping } from '@fortawesome/free-solid-svg-icons'
// regular (outlined) icons
import { faHeart as faHeartRegular } from '@fortawesome/free-regular-svg-icons'
import { library } from '@fortawesome/fontawesome-svg-core'

library.add(faMagnifyingGlass, faBagShopping, faHeartRegular)
</script>