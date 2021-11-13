<script setup>
const props = defineProps({
  fill: String,
});
</script>

<template>
  <div>
    <input
      type="text"
      class="
        p-4
        mr-3
        rounded-md
        bg-transparent
        border-gray-300 border-2
        outline-none
      "
      placeholder="Enter your e-mail"
    />
    <button
      class="
        p-4
        bg-gradient-to-t
        from-gray-700
        to-gray-600
        font-medium
        rounded-md
        shadow-2xl
        outline-none
      "
    >
      {{ fill }}
    </button>
  </div>
</template>
