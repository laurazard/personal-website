<template>
  <div id="app">
    <Header />
    <Hero />
  </div>
</template>

<script>
import Hero from "./components/Hero.vue";
import Header from "./components/Header.vue";

export default {
  name: "App",
  components: { Hero, Header },
};
</script>

<style>
</style>
