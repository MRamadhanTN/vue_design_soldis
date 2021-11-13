<script setup>
const props = defineProps({
  desk: String,
});
</script>

<template>
  <p class="py-7 text-sm w-5/12">
    {{ desk }}
  </p>
</template>
