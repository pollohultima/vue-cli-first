<template>
  <div id="app">
    <Title />
    <hero />
  </div>
</template>

<script>
import Title from "./components/Title.vue";
import Hero from "./components/Hero.vue";

export default {
  name: "App",
  components: {
    Title,
    Hero,
  },
};
</script>

<style lang="scss">
#app {
  text-align: center;
}
</style>
