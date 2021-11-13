<template>
  <div class="mx-auto bg-cover w-1298px h-451px" id="philosophy-hero-container">
    <hero-cta /> <hero-cta />
  </div>
</template>

<script>
import HeroCta from "./HeroCta.vue";

export default {
  components: { HeroCta },
};
</script>

<style>
#philosophy-hero-container {
  background-image: url(./philosophy-hero.avif);
  border-radius: 16px;
}
</style>