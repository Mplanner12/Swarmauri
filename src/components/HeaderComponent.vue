<template>
  <header class="bg-white shadow-md sticky top-0 z-50">
    <nav class="container mx-auto flex justify-between items-center p-4">
      <h1 class="text-2xl font-bold text-gray-800 uppercase">swarmakit</h1>
      <ul class="flex space-x-6 text-gray-600">
        <li><a href="#hero" class="hover:text-gray-900 transition">Home</a></li>
        <li>
          <a href="#features" class="hover:text-gray-900 transition">About</a>
        </li>
        <li>
          <a href="#contact" class="hover:text-gray-900 transition">Contact</a>
        </li>
      </ul>
      <button
        class="bg-blue-600 text-white py-2 px-4 rounded-lg hover:bg-blue-700 transition"
      >
        Get Started
      </button>
    </nav>
  </header>
</template>

<script lang="ts">
export default {
  name: "HeaderComponent",
};
</script>
