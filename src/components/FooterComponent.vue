<template>
  <footer id="contact" class="bg-gray-900 text-gray-300 py-10">
    <div class="container mx-auto text-center">
      <h2 class="text-2xl font-bold mb-6">Stay Connected</h2>
      <form
        class="flex flex-col md:flex-row justify-center space-y-4 md:space-y-0 md:space-x-4"
      >
        <input
          type="email"
          placeholder="Your Email Address"
          class="px-4 py-2 rounded-lg focus:outline-none focus:ring focus:ring-blue-500"
        />
        <!-- <Button :prop1="Subscribe"> </Button> -->
        <button
          class="bg-blue-600 text-white py-2 px-6 rounded-lg hover:bg-blue-700 transition shadow-lg"
        >
          Subscribe
        </button>
      </form>
      <p class="mt-8 text-sm">&copy; 2024 ElegantPage. All Rights Reserved.</p>
    </div>
  </footer>
</template>

<script lang="ts">
// import { Button } from "@swarmakit/vue";
export default {
  name: "FooterComponent",
};
</script>
