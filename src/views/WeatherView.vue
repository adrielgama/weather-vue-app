<script setup lang="ts">
import { Search } from 'lucide-vue-next'
</script>

<template>
  <main>
    <h1 class="bg-neutral-50 p-8 w-[30vw] h-full flex flex-col items-center space-y-4">
      <h1 class="text-neutral-700 text-3xl font-bold">Weather App</h1>
      <div class="w-full relative">
        <input
          type="text"
          placeholder="Enter location"
          class="py-2 px-4 rounded-full bg-neutral-200 w-full text-sm font-medium placeholder:font-normal placeholder:text-neutral-400 text-neutral-600"
        />
        <Search :size="20" class="absolute right-4 top-1/2 -translate-y-1/2 text-blue-600" />
      </div>
    </h1>
  </main>
</template>
