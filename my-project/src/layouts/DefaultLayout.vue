<template>
    <div class="bg-gray-900 text-white min-h-screen">
      <header class="p-6">
        <div class="container mx-auto flex justify-between items-center">
          <h1 class="text-2xl font-semibold">GWEJ BACKEND</h1>
          <nav class="space-x-6">
            <!-- <a href="#" class="hover:text-indigo-300">Home</a>
            <a href="#" class="hover:text-indigo-300">About</a>
            <a href="#" class="hover:text-indigo-300">Services</a> -->
            <!-- <a href="#" class="hover:text-indigo-300">Contact</a> -->
          </nav>
        </div>
      </header>
      <main>
        <slot />
      </main>
    </div>
  </template>
  

  <!-- <script>
import AboutSect from '../components/AboutSect.vue';

export default {
  name: 'App',
  components: {
    AboutSect,
    // ServicesSect,
    // ContactSect
  }
};
</script> -->