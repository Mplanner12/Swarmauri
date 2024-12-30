<template>
  <section id="features" class="py-20 bg-white">
    <div class="container mx-auto text-center">
      <h2 class="text-4xl font-bold text-gray-800 mb-10">Why Choose Us</h2>
      <div class="grid grid-cols-1 md:grid-cols-3 gap-10">
        <div
          class="bg-gray-100 p-6 rounded-lg shadow-lg hover:shadow-xl transition"
        >
          <img src="/speed.jpg" alt="Speed" class="w-16 h-16 mx-auto mb-4" />
          <h3 class="text-xl font-semibold mb-2 text-gray-800">Speed</h3>
          <p class="text-gray-600">
            Lightning-fast platform to keep you ahead.
          </p>
        </div>
        <div
          class="bg-gray-100 p-6 rounded-lg shadow-lg hover:shadow-xl transition"
        >
          <img src="/design.png" alt="Design" class="w-16 h-16 mx-auto mb-4" />
          <h3 class="text-xl font-semibold mb-2 text-gray-800">Design</h3>
          <p class="text-gray-600">
            Clean, modern, and intuitive designs for every user.
          </p>
        </div>
        <div
          class="bg-gray-100 p-6 rounded-lg shadow-lg hover:shadow-xl transition"
        >
          <img
            src="/support.png"
            alt="Support"
            class="w-16 h-16 mx-auto mb-4"
          />
          <h3 class="text-xl font-semibold mb-2 text-gray-800">Support</h3>
          <p class="text-gray-600">24/7 support to assist you at any time.</p>
        </div>
      </div>
    </div>
  </section>
</template>

<script lang="ts">
export default {
  name: "FeaturesComponent",
};
</script>
