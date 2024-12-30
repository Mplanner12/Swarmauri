<template>
  <section id="hero" class="bg-gray-100 py-20">
    <div
      class="container mx-auto flex flex-col-reverse lg:flex-row items-center"
    >
      <div class="w-full lg:w-1/2 text-center lg:text-left">
        <h2 class="text-5xl font-extrabold text-gray-800 leading-tight mb-6">
          Redefine Simplicity <br />
          with <span class="text-blue-600 uppercase">swarmakit</span>
        </h2>
        <p class="text-lg text-gray-600 mb-8">
          Discover a modern, clean, and intuitive platform designed to make your
          experience seamless and enjoyable.
        </p>
        <a
          href="https://www.npmjs.com/package/@swarmakit/vue"
          class="bg-blue-600 text-white py-3 px-6 rounded-lg hover:bg-blue-700 transition shadow-md"
        >
          Explore Now
        </a>
      </div>
      <div
        class="w-full lg:w-1/2 bg-blue-700 p-4 lg:py-16 rounded-lg shadow-lg lg:relative left-8"
      >
        <img
          src="/Swarmauri-logo.png"
          alt="Hero Image"
          class="rounded-lg shadow-lg"
        />
      </div>
    </div>
  </section>
</template>

<script lang="ts">
export default {
  name: "HeroComponent",
};
</script>
