<template>
  <div id="app">
    <img alt="Vue logo" src="./assets/logo.png" />
    <titolo msg="Ciao.... finalmente..." />
  </div>
</template>

<script>
import titolo from "./components/titolo.vue";

export default {
  name: "App",
  components: {
    titolo,
  },
};
</script>

<style lang="scss">
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
}
</style>
