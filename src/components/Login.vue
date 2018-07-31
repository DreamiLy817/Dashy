<template>
    <div class="container-fluid">
        <div class="sign-container">
            <div class="sign-content">
                <p>Sign in to your <br> account</p>
                <form action="">
                    <label for="email">Email</label>
                    <input type="text" name="email" id="email" required>
                    <label for="mdp">Super secret password</label>
                    <input type="password" name="mdp" id="mdp" required>
                    <input type="submit" value="Sign in!">
                </form>
                <a href="" class="content-link">Forgot your password ? Don't worry, click here :D</a>
            </div>
            <div class="sign-img">
                <div class="img-content"><img src="../assets/img/photoLogin.jpeg" alt=""></div>
                <div class="img-gradient"></div>
                <div class="img-texte">Manage your own online business, it's easier than you think</div>
            </div>
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
    background: white;
    display: flex;
    -webkit-border-radius: 20px;
    -moz-border-radius: 20px;
    border-radius: 20px;
    margin: 0 50px;
    -webkit-box-shadow: 0px 0px 53px -19px rgba(0,0,0,0.75);
    -moz-box-shadow: 0px 0px 53px -19px rgba(0,0,0,0.75);
    box-shadow: 0px 0px 53px -19px rgba(0,0,0,0.75);
    max-width: 80%;
    margin: 0 auto;
}
    .sign-content {
        width: 40%;
        padding: 40px 50px 45px 100px;
        display: flex;
        flex-direction: column;
        align-items: flex-start;
        justify-content: center;
    }
    .sign-content .content-link {
        text-align: center;
        width: 100%;
        text-decoration: none;
        font-weight: 700;
        color: #FF8F9C;
        transition: all 0.3s;
    }
.sign-content .content-link:hover {
    color: #d57683;
    transition: all 0.3s;
}
    .sign-content p:first-child {
        font-size: 50px;
        font-weight: 700;
        line-height: 40px;
    }
    .sign-img {
        width: 60%;
        overflow: hidden;
        position: relative;
        max-height: 550px;
        border-bottom-right-radius: 20px;
        border-top-right-radius: 20px;
    }
    .sign-img .img-content img {
        border-bottom-right-radius: 20px;
        border-top-right-radius: 20px;
        height: 100%;

    }
.sign-img .img-texte {
    position: absolute;
    bottom: 90px;
    left: 50px;
    color: white;
    font-size: 30px;
    width: 70%;
}
.sign-img .img-gradient {
    background: #DAD299;  /* fallback for old browsers */
    background: -webkit-linear-gradient(to bottom, #FF8F9C, #FFAF9D,#FFC69E);  /* Chrome 10-25, Safari 5.1-6 */
    background: linear-gradient(to bottom, #FF8F9C,#FFAF9D, #FFC69E); /* W3C, IE 10+/ Edge, Firefox 16+, Chrome 26+, Opera 12+, Safari 7+ */
    position: absolute;
    top: 0;
    left: 0;
    height: 100%;
    width: 100%;
    opacity: 0.7;
    border-bottom-right-radius: 20px;
    border-top-right-radius: 20px;
}
form {
        display: flex;
        flex-direction: column;
        width: 100%;
    }
    label {
        padding-bottom: 10px;
        margin: 0;
    }
    input {
        border: none;
        border-bottom: 1px solid #787878;
        padding-bottom: 10px;
        color: #787878;
        margin-bottom: 30px;
        outline: none;

    }
    input[type="submit"] {
        border: none;
        background: #DAD299;  /* fallback for old browsers */
        background: -webkit-linear-gradient(to bottom, #FF8F9C, #FFAF9D,#FFC69E);  /* Chrome 10-25, Safari 5.1-6 */
        background: linear-gradient(to bottom, #FF8F9C,#FFAF9D, #FFC69E); /* W3C, IE 10+/ Edge, Firefox 16+, Chrome 26+, Opera 12+, Safari 7+ */
        -webkit-border-radius: 50%;
        -moz-border-radius: 50%;
        border-radius: 30px;
        padding: 15px;
        color: white;
        font-weight: 700;
        font-size: 15px;
        cursor: pointer;
        transition: all 0.3s;
    }
input[type="submit"]:hover {
    transition: all 0.3s;
    background: white;
    color: #414141;
    box-shadow: -1px 0 0 1px rgba(255, 203, 82, 0.75), -1px -1px 0 1px rgba(255, 170, 70, 0.25), -1px 1px 0 1px rgba(255, 170, 70, 0.25), 0 -1px 0 1px rgba(255, 136, 57, 0.5), 0 1px 0 1px rgba(255, 136, 57, 0.5), 1px -1px 0 1px rgba(255, 103, 44, 0.25), 1px 1px 0 1px rgba(255, 103, 44, 0.25), 1px 0 0 1px rgba(255, 69, 31, 0.75);
}
    .container-fluid {
        height: 100vh;
        display: flex;
        justify-content: center;
        align-items: center;
        background: #ECE9E6;  /* fallback for old browsers */
        background: -webkit-linear-gradient(to left, #FFFFFF, #ECE9E6);  /* Chrome 10-25, Safari 5.1-6 */
        background: linear-gradient(to left, #FFFFFF, #ECE9E6); /* W3C, IE 10+/ Edge, Firefox 16+, Chrome 26+, Opera 12+, Safari 7+ */

    }
</style>
