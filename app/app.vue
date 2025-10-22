<script setup lang="ts">
import { Button } from "./components/ui/button";
</script>

<template>
  <div class="flex h-screen flex-col items-center justify-center gap-4">
    <h1 class="text-4xl font-bold">Hello World</h1>
    <NuxtImg
      src="https://placehold.co/600x400"
      alt="Nuxt logo"
      height="100"
      width="300"
      sizes="sm:100vw md:50vw lg:400px"
      format="webp"
      quality="80"
    />
    <Button>Click me</Button>
  </div>
</template>
