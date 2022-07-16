<template>
  <section id="about" class="about">
    <div class="container-fluid">
      <div class="row g-3">
        <div class="col-sm-6 col-md-6">
          <h1 class="display-1">About Us</h1>
          <p class="lead p-3 mt-3 fs-3">
            Lorem ipsum dolor sit amet, consectetur adipisicing elit.
            Reprehenderit est nisi, cupiditate culpa, vero dolore quisquam iste
            provident eveniet maiores
          </p>
        </div>
        <div class="col-sm-6 col-md-6 striped h-100 p-4">
          <StartUp />
        </div>
      </div>
    </div>
    <!-- <RampDown /> -->
  </section>
</template>

<script>
import StartUp from './webimages/StartUp.vue'
// import RampDown from './webimages/RampDown.vue'

export default {
  name: 'AboutSection',
  components: {
    StartUp,
    // RampDown,
  },
  // created() {},
  data() {
    return {}
  },
  props: {},
  methods: {},
}
</script>

<style scoped>
section.about {
  padding-top: 12rem;
  min-height: calc(100vh + 140px);
}
.about h1 {
  font-family: 'Bebas Neue', cursive;
  color: #0000ff;
}
.striped {
  display: block;
}
</style>
