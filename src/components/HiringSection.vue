<template>
  <section class="hiring" id="hiring">
    <div class="container-fluid">
      <!-- <h1 class="display-1 text-dark">Hello World</h1> -->
      <div class="row mt-5 p-2 g-2 justify-content-between">
        <div class="col-sm-12 col-md-6 border bg-light">
          <div class="col-8 team-meeting">
            <TeamMeeting />
          </div>
        </div>
        <div class="col-sm-12 col-md-5 team-credo">
          <h1 class="display-3">Lorem Ipsum</h1>
          <p class="lead fs-3 text-dark">
            Lorem ipsum dolor sit amet consectetur adipisicing elit. Eius labore
            ea quia!
          </p>
        </div>
      </div>
    </div>
  </section>
  <footer class="text-center text-lg-start text-muted bg-dark bg-light">
    <!-- Section: Social media -->
    <section
      class="d-flex justify-content-center justify-content-lg-between p-4 border-bottom"
    >
      <!-- Left -->
      <div class="me-5 d-none d-lg-block text-light">
        <span>Get connected with us on social networks:</span>
      </div>
      <!-- Left -->

      <!-- Right -->
      <div>
        <a href="" class="me-4 text-reset">
          <i class="fab fa-facebook-f"></i>
        </a>
        <a href="" class="me-4 text-reset">
          <i class="fab fa-twitter"></i>
        </a>
        <a href="" class="me-4 text-reset">
          <i class="fab fa-google"></i>
        </a>
        <a href="" class="me-4 text-reset">
          <i class="fab fa-instagram"></i>
        </a>
        <a href="" class="me-4 text-reset">
          <i class="fab fa-linkedin"></i>
        </a>
        <a href="" class="me-4 text-reset">
          <i class="fab fa-github"></i>
        </a>
      </div>
      <!-- Right -->
    </section>
    <!-- Section: Social media -->

    <!-- Section: Links  -->
    <section class="bg-dark text-gray-500">
      <div class="container text-center text-md-start mt-5">
        <!-- Grid row -->
        <div class="row mt-3">
          <!-- Grid column -->
          <div class="col-md-3 col-lg-4 col-xl-3 mx-auto mb-4">
            <!-- Content -->
            <h6 class="text-uppercase fw-bold mb-4">
              <i class="fas fa-gem me-3"></i>
              Company name
            </h6>
            <p>
              Here you can use rows and columns to organize your footer content.
              Lorem ipsum dolor sit amet, consectetur adipisicing elit.
            </p>
          </div>
          <!-- Grid column -->

          <!-- Grid column -->
          <div class="col-md-2 col-lg-2 col-xl-2 mx-auto mb-4">
            <!-- Links -->
            <h6 class="text-uppercase fw-bold mb-4">
              Products
            </h6>
            <p>
              <a href="#!" class="text-reset">Angular</a>
            </p>
            <p>
              <a href="#!" class="text-reset">React</a>
            </p>
            <p>
              <a href="#!" class="text-reset">Vue</a>
            </p>
            <p>
              <a href="#!" class="text-reset">Laravel</a>
            </p>
          </div>
          <!-- Grid column -->

          <!-- Grid column -->
          <div class="col-md-3 col-lg-2 col-xl-2 mx-auto mb-4">
            <!-- Links -->
            <h6 class="text-uppercase fw-bold mb-4">
              Useful links
            </h6>
            <p>
              <a href="#!" class="text-reset">Pricing</a>
            </p>
            <p>
              <a href="#!" class="text-reset">Settings</a>
            </p>
            <p>
              <a href="#!" class="text-reset">Orders</a>
            </p>
            <p>
              <a href="#!" class="text-reset">Help</a>
            </p>
          </div>
          <!-- Grid column -->

          <!-- Grid column -->
          <div class="col-md-4 col-lg-3 col-xl-3 mx-auto mb-md-0 mb-4">
            <!-- Links -->
            <h6 class="text-uppercase fw-bold mb-4">
              Contact
            </h6>
            <p>
              <i class="fas fa-home me-3"></i>
              New York, NY 10012, US
            </p>
            <p>
              <i class="fas fa-envelope me-3"></i>
              info@example.com
            </p>
            <p>
              <i class="fas fa-phone me-3"></i>
              + 01 234 567 88
            </p>
            <p>
              <i class="fas fa-print me-3"></i>
              + 01 234 567 89
            </p>
          </div>
          <!-- Grid column -->
        </div>
        <!-- Grid row -->
      </div>
    </section>
    <!-- Section: Links  -->

    <!-- Copyright -->
    <div class="text-center p-4 bg-black" style="font-size: small;">
      © 2021 Copyright:
      <a class="text-reset fw-bold" href="">
        Powered by Giovanni Herdigein for DinqIt
      </a>
    </div>
    <!-- Copyright -->
  </footer>
  <!-- Footer -->
</template>

<script>
import TeamMeeting from './webimages/TeamMeeting.vue'

export default {
  name: 'HiringSection',
  created() {},
  data() {
    return {}
  },
  components: {
    TeamMeeting,
  },
  props: {},
  methods: {},
}
</script>

<style scoped>
section.hiring {
  min-height: 100vh;
  padding-top: 4rem;
}
.hiring h1 {
  font-family: 'Bebas Neue', cursive;
}

.team-meeting {
  padding-right: 3.5rem;
}
.team-credo {
  margin-top: 1.2rem;
  /* margin-left: 1rem; */
}
</style>
