<template>
  <section id="profile" class="profile">
    <div class="row justify-content-between">
      <div class="col-dm-6 col-md-4">
        <FlatChart />
      </div>
      <div class="col-sm-6 col-md-6 text-center ms-2 mt-4">
        <h1 class="display-1 mt-5">Profile</h1>
        <p class="lead fs-3">
          Lorem ipsum dolor sit amet consectetur, adipisicing elit. Aliquid,
          quia!
        </p>
      </div>
    </div>
  </section>
</template>

<script>
import FlatChart from './webimages/FlatChart.vue'

export default {
  name: 'ProfileSection',
  components: {
    FlatChart,
  },
  data() {
    return {}
  },
  props: {},
  methods: {},
}
</script>

<style scoped>
.profile {
  min-height: 100vh;
  background: linear-gradient(rgb(195, 192, 192), rgb(229, 226, 226));
  padding-top: 12rem;
  padding-bottom: 3rem;
}
h1 {
  font-family: 'Bebas Neue', cursive;
}
</style>
