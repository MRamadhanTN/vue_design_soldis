<script setup>
const props = defineProps({
  title: String,
});
</script>

<template>
  <a href="#">{{ title }}</a>
</template>
