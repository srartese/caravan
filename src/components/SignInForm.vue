<template>
  <div class="signInForm"> 
          <h1>Welcome Back!</h1>
          
          <form action="/" method="post">
          
            <div class="field-wrap">
            <label>
              Email Address<span class="req">*</span>
            </label>
            <input type="email" required autocomplete="off"/>
          </div>
          
          <div class="field-wrap">
            <label>
              Password<span class="req">*</span>
            </label>
            <input type="password" required autocomplete="off"/>
          </div>
          
          <p class="forgot"><a href="#">Forgot Password?</a></p>
          
          
          </form>

  </div>
</template>

<script>
export default {
  name: 'SignInForm',
  props: {

  }
}
</script>


