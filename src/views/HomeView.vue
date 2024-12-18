<script setup lang="ts">
import CounterBody from '@/components/CounterBody.vue'
</script>

<template>
  <main class="flex flex-col gap-4 items-center justify-center h-[100vh] w-[100vw]">
    <h1 class="font-semibold text-3xl">Hello world</h1>
    <CounterBody />
    <RouterLink to="/test">Navigate</RouterLink>
  </main>
</template>
