<template>
  <div>
      <!-- landing page for mobile screen -->
    <div class=" home hidden-sm-and-up"></div> 
      <!-- landing page for mobile screen -->


     

<!-- ********************************* Body  for app *******************************************************     -->

    <div class="about" id="about">
      <v-container >
        <v-row wrap>
          <v-col cols="12" md="7">
            <v-card class="pa-5" flat>
              <h3 class="my-5">ABOUT US</h3>
              <div>
                <p> <strong>Gulfbridge Consulting Limited</strong> is a Human Resources Management, Training Services and Strategy Consulting practice based in Lagos, Nigeria. We are founded upon years of multi-sector engagement with topnotch brands with heavy realiance on technology and up-to-date technical competence to solve a business' people problems.</p>
                <p> We are a company incorporated to help businesses bridge the gap between the status quo and where they aspire to be strategy-wise, by ensuring that its people are given the tools and competences to execute their strategy per time. Our interventions address complex people needs of organizations that want to optimize performance and get greater returns for their human capital spend whilst tracking the right metrics. Our solutions address the knottiest of human capital and strategy challenges both in the public and private sectors.
                </p>
                <p>Our approach is to do little things well. We firmly believe that it is little things done well that stack up to form the solid entity that stakeholders come to trust and engage with. So, we pay premium attention to detail and systematically build to the big picture.</p>
              </div>
            </v-card>
          </v-col>

          <v-col cols="12" md="7" >
            <v-card class="pa-5" flat>
              <img src="../assets/Img1.svg" alt="" srcset="" >
            </v-card>
          </v-col>

          <v-col cols="12" md="5" class="">
            <v-card class="pa-5" flat>
              <h3 class="my-5">THE GULFBRIDGE ADVANTAGE</h3>
              <div>
                <p> We are an extremely agile organization run by passionate HR and Business Professionals with many years hands-on experience, cutting across different sectors – Hospitality & Tourism, Telecommunications, Real Estates, Aviation, Financial Services, Consulting, Not-For-Profit, Information Technology, Engineering, Media, etc. Our people are carefully selected and have high sense of responsibility. We are professional & up-to-date with the latest HR issues, debates, development and concepts. With our monthly day-long conference, we keep our people relevant, all in the process of serving you better.</p>
              </div>
            </v-card>
          </v-col>
        </v-row>
      </v-container>
    </div>
  
    <div class="service" id="service">
      <v-container>
        <v-row wrap style="margin: 0px 0px" >
          <v-col cols="12" md="7">
            <v-card class="pa-5" flat>
              <h3 class="my-5">OUR SERVICE</h3>
              <ul>
                <li>HR Advisory</li>
                <li>Service Design</li>
                <li>Business Strategy Implementation</li>
                <li>Training & Development</li>
                <li>Recruitment Services</li>
                <li>SME HR Toolkit</li>
                <li>Customer Attention, Retention & Experience (CARE) Services for SMEs</li>
                <li>Outsourcing Services</li>
              </ul>
            </v-card>
          </v-col>

          <v-col cols="12" md="5" >
            <img src="../assets/Img22.svg" alt="" srcset=""  >
          </v-col>

       

          <v-col cols="12" md="12">
            <v-card class="pa-5" flat >
              <h3 class="my-5">HOW WE SERVE YOU</h3>
              <div>
                <p> We start our engagement with you, our valued client, with a thorough understanding of your business (strategy, operating model, etc.) and its need(s). We naturally prefer to start with a brief from you to us but where that is not possible for whatever reasons, we will come in to gather information ourselves by carrying out surveys and other information gathering tools. With this knowledge, we formulate your recruitment, training and other needs, seek your approval to our proposed interventions, and we work from there by giving you a project plan.</p>
                <p>A staff is dedicated to liaise with you, so that you are kept abreast of the emerging issues and what we have done or intend to do about them. Critical issues like recruitment and other activities that have financial actions will be subject to your approval. Regular meetings at predetermined intervals will help keep you up to date on all critical aspects of issues outsourced to us so that you can devote a higher percentage of your time to other core HR issues..</p>
              </div>
            </v-card>
          </v-col>
        </v-row>
      </v-container>
     
    </div>

    <div class="footer" id="contact">
      <v-container>
        <v-row class="" style="margin-left:12px;">
          <v-col cols="12" >
            <p style="letter-spacing: 1px">+234 807 777 6770 <br>
             +234 812 695 2210 <br>
            connect@gulfbridgeconsulting.com</p>
            
          </v-col>
          <v-col cols="12">
            <span style="color: #1b3164">
            <i class="fab fa-twitter"></i>
            <i class="fab fa-facebook-f"></i>
            <i class="fab fa-instagram"></i>
            <i class="fab fa-linkedin-in"></i>
            <i class="fab fa-medium-m"></i>
          </span>
          </v-col>
          
          <v-col cols="12">
            <p>  © 2020 Gulfbridge Consulting Limited </p> 
          </v-col>
        </v-row>  
      </v-container>
    </div>  
  </div>
</template>

<script>
  export default {
    name: 'Home',

    data: () => ({
     
    }),
  }
</script>

<style lang="scss">
  .home {
    background-image: url("../assets/GBM2.png");
    background-position: center;
    background-size: cover;
    background-repeat: no-repeat;
    height: 100vh;
  }

  p {
    font-size : 14px;
    text-align: justify;
    line-height: 25px;
   // font-weight: bold;
  }

  h3 {
    display: inline-block;
    border-bottom: 4px solid pink;
    letter-spacing: 2px;
    font-weight: bolder;
  }

  ul {
    margin : 0px;

    li {
      font-size: 14px;
      letter-spacing: 1px;
      text-align: start;
      line-height: 35px;
     // font-weight: bold;
      color: #1b3164;
    }
  }
  .about div p{
    color :#1b3164;
  }
  .about div h3 {
    color: #1b3164;
  }

  .service {
    //background-color: #33a0ba;
    div p {
      color: #1b3164;
    }
    div h3 {
      color: #1b3164;
      //border-bottom: none;
    }
  }
  .footer {
    // display: block;
    background-image: url("../assets/NewFooterBg3.png");
    background-position:center;
    background-size: cover;
    background-repeat: no-repeat;
    height: 40vh;

    p {
      font-size: 14px;
      //line-height: 20px;
      font-weight: bold;
      color: #1b3164;
    }
    .fab {
      padding: 0px 10px;
    }
  }
</style>
