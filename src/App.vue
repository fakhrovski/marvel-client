<template>
  <div id="app">
  <h1 style="font-family: cursive;text-align: center">Marvel Super Heroes</h1>
  <Carousel/>
  </div>
</template>

<script>
import Carousel from "./components/carousel.vue";
export default {
  components: {
    Carousel
  }
};
</script>

<style>
#app {
  font-family: "Avenir", Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
}
</style>
