<template>

    <div class="container">
      
      <!-- imitation just to have the flip effect -->
    <input type="checkbox" id="flip">

        <div class="cover">
            <!-- front image -->
              <div class="front">
                <img src="../assets/Home_01_Agentur_01.jpg" alt="">
                <div class="text">
                  <span class="text-1">Digital Media Experiences</span>
                  <span class="text-2">Agentur für digitale Markenerlebnisse.</span>
                </div>
              </div>

            <!-- back image  -->
              <div class="back">
                <img  src="../assets/Home_01_Agentur_01.jpg" alt="">
                <div class="text">
                  <span class="text-1">Complete miles of journey <br> with one step</span>
                  <span class="text-2">Let's get started</span>
                </div>
              </div>

        </div>

    <!-- form class start -->
        <div class="forms">
            <div class="form-content">
              <!-- Login Form start -->
            <div class="login-form">

                    <div class="title"><img src="../assets/logo.png">
                      <br>Login
                    </div>
                    
                <form action="#">
                  <div class="input-boxes">

                      <div class="input-box">
                        <i class="fas fa-envelope"></i>
                        <input type="email" placeholder="Enter your email" required>
                      </div>

                      <div class="input-box">
                        <i class="fas fa-lock"></i>
                        <input type="password" placeholder="Enter your password" required>
                      </div>

                      <div class="text"><a href="#">Forgot password?</a></div>

                      <div class="button input-box">
                        <input type="submit" value="Sign In">
                      </div>

                    <div class="text sign-up-text">Don't have an account? <label for="flip">Sigup now</label></div>
                  </div>
                </form>

            </div>
                <!-- Login Form end -->

             <!-- Sign Up Form start -->

          <div class="signup-form">
                <div class="title">
                  <img src="../assets/logo.png"><br>
                    Signup
                </div>
              <form action="#">
                <div class="input-boxes">

                  <div class="input-box">
                    <i class="fas fa-user"></i>
                    <input type="text" placeholder="Enter your name" required>
                  </div>

                  <div class="input-box">
                    <i class="fas fa-envelope"></i>
                    <input type="email" placeholder="Enter your email" required>
                  </div>

                  <div class="input-box">
                    <i class="fas fa-lock"></i>
                    <input type="password" placeholder="Enter your password" required>
                  </div>

                  <div class="button input-box">
                    <input type="submit" value="Sign Up">
                  </div>
                  
                  <div class="text sign-up-text">Already have an account? <label for="flip">Login now</label></div>
                </div>
              </form>
            </div>

        <!-- Sign Up Form end -->

      </div>
    </div>
        <!-- form class end -->

  </div>


</template>

