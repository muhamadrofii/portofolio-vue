<!-- <script setup>
import LandingPage from './components/LandingPage.vue'
</script>

<template>
  <LandingPage/>
</template> -->


<template>
    <div id="app" class="font-poppins">
      <DefaultLayout>
        <HeroSection />
        <AboutSect />
        <PortfolioSection />
      </DefaultLayout>
    <!-- <h1 class="text-2xl font-bold">Welcome to Vue.js with Poppins Font</h1> -->
  </div>
</template>

<script setup>
import DefaultLayout from './layouts/DefaultLayout.vue'
import HeroSection from './components/HeroSection.vue'
import AboutSect from './components/AboutSect.vue'
import PortfolioSection from './components/PortfolioSection.vue';

// export default {
//   name: 'App'
// }
</script>




