<script setup lang="ts">
import VTabs from './components/tabs/VTabs.vue'
import VTab from './components/tabs/VTab.vue'
</script>

<template>
  <div class="flex flex-col justify-between max-w-screen-sm mx-auto min-h-screen py-10">
    <div>
      <h1 class="text-2xl font-bold text-center mb-10">
        Examples of Vue 3 components for copy-pasting into your project 😉
      </h1>
      <h2 class="text-xl font-bold mb-8">Tabs</h2>
      <VTabs>
        <VTab title="Tab 1">Content 1</VTab>
        <VTab title="Tab 2">Content 2</VTab>
        <VTab title="Tab 3">Content 3</VTab>
      </VTabs>
    </div>
    <div class="text-center">
      View code on my <a href="https://github.com/leshkin/vue-3-examples" class="underline">GitHub</a>
    </div>
  </div>
</template>
