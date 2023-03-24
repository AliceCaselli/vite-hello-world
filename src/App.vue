<script>
import AppTitle from "./components/AppTitle.vue";
import AppHero from "./components/AppHero.vue";
// funzionalità

export default {
  data() {
    return {

    };
  },

  components: {
    AppTitle,
    AppHero,
  }
}
</script>

<template>
  <!-- layout -->
  <div class="container">
    <AppHero></AppHero>

    <AppTitle></AppTitle>
  </div>
</template>

<style scoped>
/* stile */

.container {
  display: flex;
  justify-content: center;
}
</style>