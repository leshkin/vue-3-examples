<script setup lang="ts">
import VTabs from './components/tabs/VTabs.vue'
import VTab from './components/tabs/VTab.vue'
</script>

<template>
  <h1 class="text-2xl font-bold my-8">Examples of Vue 3 components for copy-pasting into your project 😉</h1>
  <h2 class="text-xl font-bold my-8">Tabs</h2>
  <VTabs>
    <VTab title="Tab 1">Content 1</VTab>
    <VTab title="Tab 2">Content 2</VTab>
    <VTab title="Tab 3">Content 3</VTab>
  </VTabs>
</template>
