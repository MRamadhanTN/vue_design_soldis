<script setup>
const props = defineProps({
  title: String,
});
</script>

<template>
  <h1 class="flex items-center text-7xl w-9/12">{{ title }}</h1>
</template>
