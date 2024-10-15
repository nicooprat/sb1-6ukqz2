<script setup lang="ts">
import { ref } from 'vue';

defineProps<{ msg: string }>();

const count = ref(0);
</script>

<template>
  <h1 class="text-4xl font-bold mb-4">{{ msg }}</h1>

  <div class="card">
    <button type="button" @click="count++" class="mb-4">
      count is {{ count }}
    </button>
    <p>
      Edit
      <code class="font-mono bg-gray-200 dark:bg-gray-800 px-1 rounded"
        >components/HelloWorld.vue</code
      >
      to test HMR
    </p>
  </div>

  <p class="mt-4">
    Check out
    <a
      href="https://vuejs.org/guide/quick-start.html#local"
      target="_blank"
      class="font-medium text-blue-600 dark:text-blue-400"
      >create-vue</a
    >, the official Vue + Vite starter
  </p>
  <p class="mt-2">
    Learn more about IDE Support for Vue in the
    <a
      href="https://vuejs.org/guide/scaling-up/tooling.html#ide-support"
      target="_blank"
      class="font-medium text-blue-600 dark:text-blue-400"
      >Vue Docs Scaling up Guide</a
    >.
  </p>
  <p class="read-the-docs mt-4">
    Click on the Vite and Vue logos to learn more
  </p>
</template>
