<script setup lang="ts">
import HelloWorld from './components/HelloWorld.vue'
</script>

<template>
  <div class="flex justify-center space-x-4 mb-8">
    <a href="https://vitejs.dev" target="_blank">
      <img src="/vite.svg" class="logo h-24 p-6 transition-all duration-300 hover:drop-shadow-[0_0_2em_#646cffaa]" alt="Vite logo" />
    </a>
    <a href="https://vuejs.org/" target="_blank">
      <img src="./assets/vue.svg" class="logo h-24 p-6 transition-all duration-300 hover:drop-shadow-[0_0_2em_#42b883aa]" alt="Vue logo" />
    </a>
  </div>
  <HelloWorld msg="Vite + Vue" />
</template>