<script setup>

</script>

<!-- <template>
  <body> -->
    <!-- <div class="nav">
    <RouterLink to="/" class="nav-item">Home</RouterLink>
        <RouterLink to="/Login" class="nav-item">Login</RouterLink>
        <RouterLink to="/Signup" class="nav-item">Signup</RouterLink> 
        <RouterLink to="/Logout" class="nav-item"> Logout</RouterLink>
      

 </div> -->
 <!-- <nav class="navbar navbar-expand-lg navbar-dark bg-dark">
  <div class="container-fluid">
    <a class="navbar-brand" href="#">Welcome</a>
    <button class="navbar-toggler" type="button" data-bs-toggle="collapse" data-bs-target="#navbarNavAltMarkup" aria-controls="navbarNavAltMarkup" aria-expanded="false" aria-label="Toggle navigation">
      <span class="navbar-toggler-icon"></span>
    </button>
    <div class="collapse navbar-collapse show" id="navbarNavAltMarkup">
      <div class="navbar-nav">
        <a class="nav-link active" aria-current="page" href="Home.vue">Home</a>
        <a class="nav-link active" href="/Login.vue">Login</a>
        <a class="nav-link active" href="/Signup.vue">Signup</a>
        <a class="nav-link active" href="/Logout.vue">Logout</a>
        <routerView></routerView> 
      </div>
   
    </div>
  </div>
</nav>
</body> -->

<template>
  <div>
  <nav class="navbar navbar-expand-lg navbar-light bg-blue">
    <div class="container-fluid">
      <a class="navbar-brand" href="#">Welcome</a>
      <button class="navbar-toggler" type="button" data-bs-toggle="collapse" data-bs-target="#navbarNavAltMarkup" aria-controls="navbarNavAltMarkup" aria-expanded="false" aria-label="Toggle navigation">
        <span class="navbar-toggler-icon"></span>
      </button>
      <div class="collapse navbar-collapse show" id="navbarNavAltMarkup">
        <div class="navbar-nav">
          <router-link to="/" class="nav-link">Home</router-link>
          <router-link to="/Login" class="nav-link">Login</router-link>
          <router-link to="/Signup" class="nav-link">Signup</router-link>
          <router-link to="/Logout" class="nav-link">Logout</router-link>
          <!-- <router-link to="/forgot" class="nav-link">Forgot</router-link> -->

          <routerView></routerView> 
        </div>
       
      </div>
    </div>
  </nav>
  </div>
</template>




<style scoped>

/* body {
  display: flex;
flex-direction: row;
  /* background-color: burlywood; 
  width: 100%;
}
.nav {

  padding-top: 10px;
  width: 100%;
}
/* .nav-item {
 background-color: #007bff;
  color:white;
  text-decoration: none;
  height: 50px;
  /* width: 100%; 
  padding: 30px 55px;
  font-weight: bold;
} */ 

</style>

