<template>
    <div class="portfolio-item p-4 border border-gray-300 rounded-lg shadow hover:shadow-lg transition-shadow duration-300">
      <h3 class="text-xl font-bold mb-2">{{ project.title }}</h3>
      <p class="text-gray-700 mb-4">{{ project.description }}</p>
      <a :href="project.link" target="_blank" class="text-teal-500 hover:text-teal-700">View Project</a>
    </div>
  </template>
  
  <script setup>
  const props = defineProps({
    project: {
      type: Object,
      required: true
    }
  });
  </script>
  