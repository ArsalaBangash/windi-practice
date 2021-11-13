<template>
  <div class="h-screen" id="app">
    <philosophy-hero />
  </div>
</template>

<script lang="ts">
import PhilosophyHero from "./components/PhilosophyHero.vue";

export default {
  components: { PhilosophyHero },
};
</script>


<style>
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
}
</style>