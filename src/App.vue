<script>
import Title from "./components/AppTitle.vue";
import Jumbo from "./components/AppHero.vue";
// funzionalità

export default {
  data() {
    return {

    };
  },

  components: {
    Title,
    Jumbo,
  }
}
</script>

<template>
  <!-- layout -->
  <div class="container">
    <Jumbo></Jumbo>

    <Title></Title>
  </div>
</template>

<style scoped>
/* stile */

.container {
  display: flex;
  justify-content: center;
}
</style>