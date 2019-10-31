<template>

  <div>


    <div class="hero" id="home">
      <nav class="navbar navbar-expand-lg navbar-transparent nav-zed">

        <div class="container">

          <a class="navbar-brand" href="#">


            <img class="img-fluid logo" src="../assets/logo.svg">

          </a>
          <button class="navbar-toggler" type="button" data-toggle="collapse" data-target="#navbarSupportedContent"
                  aria-controls="navbarSupportedContent" aria-expanded="false" aria-label="Toggle navigation">
            <span class="navbar-toggler-icon"></span>
          </button>

          <div class="collapse navbar-collapse" id="navbarSupportedContent">
            <ul class="navbar-nav ml-auto">

              <li class="nav-item active">
                <a class="nav-link" href="#" v-scroll-to="'#home'">Home</a>
              </li>
              <li class="nav-item">
                <a class="nav-link" href="#" v-scroll-to="'#service'">Service</a>
              </li>

              <li class="nav-item">
                <a class="nav-link" href="#" v-scroll-to="'#project'">Project</a>
              </li>

              <li class="nav-item">
                <a class="nav-link" href="#" v-scroll-to="'#team'">Team</a>
              </li>


              <li class="nav-item">
                <a class="nav-link" href="#" v-scroll-to="'#expertise'">Expertise</a>
              </li>

              <li class="nav-item">
                <a class="nav-link" href="#">Get in touch</a>
              </li>


            </ul>

          </div>
        </div>
      </nav>


      <div class="container">
        <div class="row align-items-center" style="min-height: 100vh">
          <div class="col">

            <div class="mb-5">
              <h1>Better Institutions,</h1>
              <h1>Better Outcome.</h1>
              <div>
                In a rapidly changing the world, we have a expertise to help our clients keep up.
              </div>
            </div>

            <button type="button" class="btn btn-purple">SEE OUR SERVICE</button>

          </div>
        </div>
      </div>


    </div>

    <div class="bg-smoke">
      <div class="container">

        <!-- project -->
        <div class="select" id="project">
          <h1 class="title">Explore our lasted projects</h1>
          <div class="mb-5">But I must explain to you how all this mistaken idea
            of denouncing pleasure and praising pain was born.
          </div>

          <div class="row">
            <div class="col-12 col-sm-6 mb-5">
              <div class=" project-1">
                <div class="row align-items-end project-card">
                  <div class="col">
                    <small>A Ministry of Finance * Latin America & the Caribbean</small>
                    <h3>Evaluation of National Customs Department Modernization Project</h3>
                  </div>
                </div>
              </div>

            </div>
            <div class="col-12 col-sm-6 mb-5">


              <div class=" project-2">
                <div class=" row align-items-end project-card">
                  <div class="col">
                    <small>National Housing Organization * Latin America & the Caribbean</small>
                    <h3>Institutional Strengthening of a National Housing Organization</h3>
                  </div>
                </div>

              </div>


            </div>
          </div>
          <div class="text-center">
            <button type="button" class="btn btn-purple">VIEW ALL PROJECTS</button>
          </div>
        </div>
        <!-- end project -->
      </div>
    </div>


    <div class="container">
      <!-- about -->
      <div class="select" id="aboutus">
        <div class="row">
          <div class="col-12 col-sm-4">
            <h1 class="title">About Us</h1>
          </div>

          <div class="col-12 col-sm-8">
            <div class="mb-3">
              International Financial Consulting is a boutique firm of global experts working with development finance
              institutions around the world on a wide range of challenges, from strategy and governance to the design
              and
              marketing of financial instruments. We combine senior expertise with data-driven insights and customized
              advisory services to help our clients realize their full potential as catalysts for development, trade,
              and
              economic growth.
            </div>

            <button type="button" class="btn btn-purple">LEARN MORE</button>
          </div>
        </div>
      </div>
      <!-- end about -->


      <!-- team -->
      <div class="select" id="team">
        <div class="row align-items-center">

          <div class="col-12 col-sm-6">
            <img class="img-fluid" src="../assets/image/team.png">
          </div>

          <div class="col-12 col-sm-6">
            <h1 class="title">Our people, our advantage</h1>
            <div>
              Our team of international experts are why clients recommend us. We combine unparalleled expertise and
              thought leadership on trade and development finance with practical hands-on experience.
            </div>
          </div>

        </div>
      </div>
      <!-- end team -->


      <!-- service -->
      <div class="select" id="service">
        <div class="row align-items-center">


          <div class="col-12 col-sm-6">
            <h1 class="title">Services</h1>

            <div class="mb-3">
              We know what it takes to run successful public-policy based institutions. Our core competency is in
              institutional development, including strategic planning, evaluation, policy formulation and programming,
              product innovation, governance systems and risk management.
            </div>

            <button type="button" class="btn btn-purple">OUR SERVICES</button>

          </div>


          <div class="col-12 col-sm-6">
            <img class="img-fluid" src="../assets/image/services.png">
          </div>

        </div>
      </div>
      <!-- end service -->


      <!-- expertise -->
      <div class="select" id="expertise">
        <div class="row align-items-center">

          <div class="col-12 col-sm-6">
            <img class="img-fluid" src="../assets/image/expertise.png">
          </div>

          <div class="col-12 col-sm-6">
            <h1 class="title">Expertise</h1>
            <div class="mb-3">
              We have extensive experience across all areas of development finance, including trade, export and
              investment, development finance and climate finance. Our expert team brings a unique combination of deep
              knowledge and expert perspectives to our client's challenges,
              offering fresh ideas and breakthrough insights.
            </div>

            <div class="mb-3">
              <small>
                If you are in the market for a computer,<br> there are a number of factors to consider.
              </small>
            </div>

            <div>
              <button type="button" class="btn btn-purple">OUR EXPERTISE</button>
            </div>
          </div>
        </div>
      </div>
      <!-- end expertise -->
    </div>


    <!-- footer -->
    <div class="footer">

      <div class="container select">

        <div class="row">
          <div class="col-12 col-sm-6">
            <h1> Get in touch </h1>
            <div class="mb-3">
              We help organizations with their most critical challenges and opportunities. Contact us now to learn how
              we can work together.
            </div>
            <button type="button" class="btn btn-white">CONTACT</button>
          </div>

          <div class="col-12 col-sm-6">
            <h1> Work with Us </h1>
            <div class="mb-3">
              We're on a mission to change the world. Learn how you can join a team focused on providing top tier advice
              and innovative, but workable solutions to our clients.
            </div>
            <button type="button" class="btn btn-white">CAREERS</button>
          </div>
        </div>
      </div>


      <hr>

      <div class="container select">
        <div class="row mb-5">
          <div class="col-12 col-sm-3"><img class="img-fluid logo" src="../assets/logo.svg"></div>
          <div class="col-12 col-sm-3">
            <div class="mb-3">
              <h5>
                PHONE
              </h5>

              <div>
                +1 123 345 2234
              </div>
            </div>
            <div>

              <h5>
                EMAIL
              </h5>

              <div>
                info@zed.xyz
              </div>

            </div>
          </div>
          <div class="col-12 col-sm-3">
            <div>
              <h5>
                SOCIAL
              </h5>

              <div>
                Linkedin
              </div>
              <div>
                Facebook
              </div>
              <div>
                Twitter
              </div>

            </div>
          </div>
          <div class="col-12 col-sm-3">

            <div>
              <h5>
                MAILING ADDRESS
              </h5>

              <div>
                Zed Financial Consulting Ltd.
                World Exchange Plaza
                P.O. Box 811219
                Ottawa, Ontario. K1P 1B1
                Canada
              </div>

            </div>

          </div>
        </div>


        <small>
          © 2019 Zed Financial Consulting LTD. Privacy Policy.
        </small>

      </div>
    </div>
    <!-- end footer -->


  </div>
</template>

<script>

  export default {
    components: {}
  }
</script>

