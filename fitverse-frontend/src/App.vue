<script setup lang="ts">
import { RouterView } from 'vue-router'
</script>

<template>
  <div class="w-full h-full flex items-center justify-center">
    <div class="w-2/3 lg:w-1/3 py-12 bg-slate-800 text-center rounded-lg shadow shadow-slate-700 opacity-80">
      <RouterView />
    </div>
  </div>
</template>

<style scoped>

</style>
