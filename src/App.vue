<script lang="ts" setup>
import Button from "./components/Button.vue";
import SampleCard from "./components/SampleCard.vue";
</script>

<template>
  <div class="min-h-screen bg-blue-lighter">
    <div class="container mx-auto text-center py-10">
      <h1 class="text-blue-darker font-bold text-3xl">Tailwind Demo</h1>
      <Button class="mt-6">Click me!</Button>
      <div class="grid grid-cols-2 lg:grid-cols-3 gap-4 px-6">
        <SampleCard />
        <SampleCard />
        <SampleCard />
        <SampleCard />
        <SampleCard />
      </div>
    </div>
  </div>
</template>
