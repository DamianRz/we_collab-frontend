<template>
  <div>
    <img alt="Vue logo" src="./assets/logo.png" />
    <hello-world />
    <home />
  </div>
</template>

<script>
import HelloWorld from "./components/HelloWorld.vue";
import Home from "../src/pages/home/home.vue";

export default {
  name: "App",
  components: {
    HelloWorld,
    Home,
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
