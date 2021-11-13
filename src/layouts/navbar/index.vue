<script setup>
import Logo from "./sections/logo.vue";
import Nav from "./sections/nav.vue";
import Contact from "./sections/contact.vue";
</script>

<template>
  <div class="flex justify-between py-8 border-b text-white">
    <div class="flex gap-12">
      <Logo />

      <Nav />
    </div>

    <Contact />
  </div>
</template>
