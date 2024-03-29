<script setup>

</script>

<template>
  <body>
    <div class="nav">
    <RouterLink to="/" class="nav-item">Home</RouterLink>
        <RouterLink to="/Login" class="nav-item">Login</RouterLink>
        <RouterLink to="/Signup" class="nav-item">Signup</RouterLink> 
        <RouterLink to="/Logout" class="nav-item"> Logout</RouterLink>
      
 <routerView></routerView> 
 </div>
</body>

</template>


<style scoped>
body {
  display: flex;
flex-direction: row;
  /* background-color: burlywood; */
  width: 100%;
}
.nav {

  padding-top: 10px;
  width: 100%;
}
.nav-item {
 background-color: #007bff;
  color:white;
  text-decoration: none;
  height: 50px;
  /* width: 100%; */
  padding: 30px 55px;
  font-weight: bold;
}

</style>

