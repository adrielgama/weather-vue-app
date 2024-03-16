<script setup lang="ts">
import DetailWeather from './DetailWeather.vue'
import WeatherView from './WeatherView.vue'
</script>

<template>
  <main class="flex w-screen h-screen bg-neutral-200">
    <WeatherView />
    <DetailWeather />
  </main>
</template>
