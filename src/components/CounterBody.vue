<script setup lang="ts">
import { ref } from 'vue'
import IncrementButton from './IncrementButton.vue'

const counter = ref(0)
</script>

<template>
  <div class="flex flex-col gap-2 items-center justify-center">
    <p>{{ counter }}</p>
    <IncrementButton v-on:click="() => counter++" />
  </div>
</template>
