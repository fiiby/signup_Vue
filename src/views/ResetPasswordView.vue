<template>
    <div class="reset-password">
      <header>
        <h1>Reset Password</h1>
      </header>
  
      <main>
        <div class="form-container">
          <form @submit.prevent="resetPassword">
            <input type="email" placeholder="Enter your email" v-model="email">
            <input type="submit" value="ResetPassword">
          </form>
        </div>
      </main>
  
      <footer>
        <p>Remembered your password? <router-link to="/login">Login</router-link></p>
      </footer>
    </div>
  </template>
  
  <script setup>
  import { ref } from 'vue';
  
  const email = ref('');
  
  const resetPassword = async () => {
    console.log(`Reset password requested for email: ${email.value}`);
    // Add logic to handle password reset here (e.g., send a reset email)
  };
  </script>
  
  <style scoped>
  /* General Styles */
  .reset-password {
    display: flex;
    flex-direction: column;
    justify-items: center;
    padding-top: 100px;
    margin-right: 400px;
    min-height: 200vh;
    min-width: 50vh;
  } 
  
  header, footer {
    background-color: rgba(141, 21, 145, 0.911);
    color: white;
    padding: 20px;
  }
  
  main {
    display: flex;
    justify-content: center;
    align-items: center;
  }
  
  form {
    width: 400px;
    padding: 20px;
    border: 1px solid #ccc;
    border-radius: 5px;
  }
  
  input {
    display: block;
    width: 100%;
    margin-bottom: 10px;
    padding: 8px;
    border: 1px solid #ccc;
    border-radius: 3px;
  }
  
  input[type="submit"] {
    background-color: #007bff;
    color: white;
    cursor: pointer;
  }
  
  input[type="submit"]:hover {
    background-color: #0056b3;
  }
  
  footer p {
    text-align: center;
  }
  
  footer a {
    color: #007bff;
    text-decoration: none;
  }
  
  footer a:hover {
    text-decoration: underline;
  }
  </style>
  