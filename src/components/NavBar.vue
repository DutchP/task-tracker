<template>
  <nav class="navbar navbar-expand-lg navbar-dark bg-black shadow sticky-top">
    <div class="container-fluid">
      <a class="navbar-brand" href="#">
        <WebLogo class="ms-2 me-auto" />
        Task Tacker
      </a>
      <button
        class="navbar-toggler"
        type="button"
        data-bs-toggle="collapse"
        data-bs-target="#navbarScroll"
        aria-controls="navbarScroll"
        aria-expanded="false"
        aria-label="Toggle navigation"
      >
        <span class="navbar-toggler-icon"></span>
      </button>
      <div
        class="collapse navbar-collapse justify-content-end me-5"
        id="navbarScroll"
      >
        <ul
          class="navbar-nav my-2 my-lg-0 navbar-nav-scroll"
          style="--bs-scroll-height: 100px;"
        >
          <li class="nav-item">
            <a class="nav-link active" aria-current="page" href="#">Home</a>
          </li>
          <li class="nav-item">
            <a class="nav-link" href="#about">About</a>
          </li>

          <li class="nav-item">
            <a class="nav-link" href="#profile">
              Profile
            </a>
          </li>

          <li class="nav-item">
            <a class="nav-link" href="#pricing">
              Pricing
            </a>
          </li>

          <li class="nav-item">
            <a class="nav-link" href="#hiring">
              Hiring
            </a>
          </li>
        </ul>
        <ul class="nav">
          <li class="nav-item">
            <a class="nav-link" style="color: #ffc107;" href="#">
              Users online
              <span
                class="ms-2 indicator bg-warning text-dark rounded-pill badge"
              >
                {{ item }}
              </span>
            </a>
          </li>
        </ul>
      </div>
    </div>
  </nav>
</template>
<script>
import WebLogo from './webimages/WebLogo.vue'
export default {
  name: 'NavBar',
  components: {
    WebLogo,
  },
  data() {
    return {}
  },
  props: {
    item: Number,
  },
}
</script>
<style scoped>
.indicator {
  text-align: center;
}
</style>
