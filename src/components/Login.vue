<template>
   <div class="sign-container">
      <div class="sign-content">
         <p>Sign in to your account</p>
         <form action="/action_page.php">
             <label for="email">Email</label>
             <input type="text" name="email" id="email" required>
             <label for="mdp">Super secret password</label>
             <input type="password" name="mdp" id="mdp" required>
             <input type="submit" value="Submit">
         </form>
         <p>Forgot your password ? Don't worry, click here :D</p>
      </div>
      <div class="sign-img">
          <div><img src="../assets/img/photoLogin.jpeg" alt=""></div>
          <div></div>
          <div>Manage your own online business, it's easier than you think</div>
      </div>
   </div>
</template>

<script>
export default {
  name: 'Home',
  data () {
    return {
      msg: 'Welcome'
    }
  }
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
.sign-container {
    display: flex;
}
    .sign-content {
        width: 50%;
    }
    .sign-img {
        width: 50%;
    }
</style>
