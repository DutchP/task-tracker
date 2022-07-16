<template>
  <NavBar :item="item" />
  <HomeSection />
  <AboutSection />
  <ProfileSection />
  <PricingSection />
  <HiringSection />
</template>

<script>
import NavBar from './components/NavBar.vue'
import HomeSection from './components/HomeSection.vue'
import AboutSection from './components/AboutSection.vue'
import ProfileSection from './components/ProfileSection.vue'
import PricingSection from './components/PricingSection.vue'
import HiringSection from './components/HiringSection.vue'

export default {
  name: 'App',
  data() {
    return {
      item: 12,
    }
  },
  components: {
    NavBar,
    HomeSection,
    AboutSection,
    ProfileSection,
    PricingSection,
    HiringSection,
  },
}
</script>

<style>
* {
  font-family: 'Palanquin', sans-serif;
}
</style>
