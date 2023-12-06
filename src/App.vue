<script>
import Titolo from "./components/FirstComponent.vue";
import Jumbotron from "./components/Jumbotron.vue";

export default {
  name: "Main",
  data() {
    return {
      title: "Questo é il mio primo sito con vite e vue js",
    };
  },
  components: {
    Titolo,
    Jumbotron,
  },
};
</script>

<template>
  <Titolo />
  <Jumbotron />
</template>

<style scoped></style>
