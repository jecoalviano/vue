<template>
<div>
    <nav class="navbar container navbar-expand-md navbar-dark bg-transparent">
  <a class="navbar-brand" href="#">
    <img src="images/logo.png" width="100" height="80" alt="" >
  </a>

  <button class="navbar-toggler" type="button" data-toggle="collapse" data-target="#navbarSupportedContent" aria-controls="navbarSupportedContent" aria-expanded="false" aria-label="Toggle navigation">
    <span class="navbar-toggler-icon"></span>
  </button>
  
    <div class="collapse navbar-collapse" id="navbarResponsive"> 
      <ul class="navbar-nav ml-auto">
        <li class="nav-item border-md-right">
         <router-link class="nav-link" :to="'/'" exact>Home</router-link>
        </li>
        <li class="nav-item border-md-right">
          <router-link class="nav-link" :to="'/contact'">Contact Us</router-link>
        </li>
        <li class="nav-item">
        <router-link class="nav-link" :to="'/login'">Login</router-link>

        </li>
      </ul>
    </div>
    
  </nav>
</div>
</template>

<script>
export default {
  name: 'Nav',
}

</script>