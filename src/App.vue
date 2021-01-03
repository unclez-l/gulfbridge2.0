<template>
  <v-app id="app"> 
    <div class="landing-page hidden-xs-only"> 
      <div>
        <v-app-bar color="white" app >
          <img src="./assets/gb-logo.svg"   style="width: 70px" alt="" srcset="" class="ml-5">
          <v-toolbar-title class="ml-4 mt-3" style="letter-spacing: 2px; font-weight: bold; font-size: 15px; color: #33a0ba">Gulfbridge Consulting</v-toolbar-title>
            <v-spacer></v-spacer>
            <div class="btn my-3 mt-5">
              <v-btn text small class="text-lowercase"><a href="#" style="text-decoration: none; color:#33a0ba">Home</a></v-btn>
              <v-btn text small class="text-lowercase"><a href="#about" style="text-decoration: none; color:#33a0ba">About us</a></v-btn>
              <v-btn text small class="text-lowercase"><a href="#service" style="text-decoration: none; color:#33a0ba">Our service</a></v-btn>
              <v-btn text small class="text-lowercase"><a href="#team" style="text-decoration: none; color:#33a0ba">Our team</a></v-btn>
              <v-btn text small class="text-lowercase"><a href="#contact" style="text-decoration: none; color:#33a0ba">Contact</a></v-btn>
            </div>
        </v-app-bar>

        <div style="color: #1b3164;">
          <div class="animate__animated animate__fadeInLeftBig animate__delay-2s">
            <p style="margin:250px 0px 0px 35px; font-size: 20px;font-weight: bold; letter-spacing:2px;">WE ARE THE BEST AT</p>
            <p  style="margin: 20px 0px 0px 35px; font-size: 15px; line-height: 25px; font-weight:bold; letter-spacing: 1px; ">HR Advisory, Training, Recruitment and providing <br>
              Professional HR Management & Advisory Services to suit <br>
              your unique operations.</p>
          </div>
          
          <div class="animate__animated animate__bounceIn animate__delay-4s">
            <span>
            <a href="https://twitter.com/GulfbridgeC" target="blank"><i class="iconz fab fa-twitter"></i></a>
            <!-- <i class="iconz fab fa-facebook-f"></i> -->
            <a href="https://www.instagram.com/gulfbridgeconsulting/?hl=en" target="_blank"><i class="iconz fab fa-instagram"></i></a>
            <a href="https://www.linkedin.com/company/gulfbridge-consulting" target="_blank"> <i class="iconz fab fa-linkedin-in"></i></a>
            <!-- <i class="iconz fab fa-medium-m"></i> -->
            </span>
          </div>
        </div>
      </div>
    </div>


    <v-content style="padding: 0px;"> <!-- removes padding on mobile screen view as a result of fixed menu/nav bar -->
      <Home/>
    </v-content>
  </v-app>
</template>

<script>
import Home from './components/Home'

export default {
  name: 'App',

  components: {
    Home,
  
  },

  data: () => ({
    //
  }),
};
</script>


<style lang="scss">
  @import url('https://fonts.googleapis.com/css2?family=Montserrat&display=swap');

 #app {
  font-family: 'Montserrat', sans-serif;
}

.landing-page {
  background-image: url("./assets/HomeBg.png");
  background-position: center;
  background-repeat: no-repeat;
  background-size: cover;
  height: 100vh;
}

.iconz {
  margin: 80px 0px 0px 30px;
  cursor: pointer;
}


</style>
