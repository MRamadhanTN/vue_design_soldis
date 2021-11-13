<script setup>
import Navbar from "./layouts/navbar/index.vue";
import Banner from "./layouts/banner/index.vue";
import Footer from "./layouts/footer/index.vue";
</script>

<template>
  <div class="bg-gradient-to-tr from-blue-900 to-purple-300 font-sans">
    <div class="container px-10 mx-auto">
      <Navbar />

      <Banner />

      <Footer>
        <svg
          xmlns="http://www.w3.org/2000/svg"
          class="h-2 w-2"
          viewBox="0 0 20 20"
          fill="currentColor"
        >
          <path
            fill-rule="evenodd"
            d="M15.707 4.293a1 1 0 010 1.414l-5 5a1 1 0 01-1.414 0l-5-5a1 1 0 011.414-1.414L10 8.586l4.293-4.293a1 1 0 011.414 0zm0 6a1 1 0 010 1.414l-5 5a1 1 0 01-1.414 0l-5-5a1 1 0 111.414-1.414L10 14.586l4.293-4.293a1 1 0 011.414 0z"
            clip-rule="evenodd"
          />
        </svg>
      </Footer>
    </div>
  </div>
</template>
