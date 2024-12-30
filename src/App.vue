<template>
  <div class="bg-gray-700">
    <HeaderComponent />
    <HeroComponent />
    <FeaturesComponent />
    <FooterComponent />
  </div>
</template>

<script lang="ts">
import HeaderComponent from "./components/HeaderComponent.vue";
import HeroComponent from "./components/HeroComponent.vue";
import FeaturesComponent from "./components/FeaturesComponent.vue";
import FooterComponent from "./components/FooterComponent.vue";

export default {
  name: "App",
  components: {
    HeaderComponent,
    HeroComponent,
    FeaturesComponent,
    FooterComponent,
  },
};
</script>

<style>
body {
  font-family: "Inter", sans-serif;
  margin: 0;
  background-color: #f9fafb;
}
</style>
