<template>
  <img alt="Vue logo" src="./assets/logo.png" />
  <HelloWoorld msg="Welcome to Your Vue.js App" />
  <FirstOne />
</template>

<script>
import HelloWoorld from "./components/HelloWoorld.vue";
import FirstOne from "./components/FirstOne.vue";

export default {
  name: "App",
  components: {
    HelloWoorld,
    FirstOne,
  },
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
