<script setup>
const props = defineProps({
  integer: Number,
  title: String,
  content: String,
});
</script>

<template>
  <div class="w-40">
    <div class="flex gap-5 mb-3">
      <p>{{ integer }}</p>
      <p class="font-bold">{{ title }}</p>
    </div>
    <div class="">{{ content }}</div>
  </div>
</template>
