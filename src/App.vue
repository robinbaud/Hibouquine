<template>
  <div id="app">
    <HomeVue />
    <AddAnnounce />
    <Register />
  </div>
</template>

<script>
import HomeVue from "./components/pages/Home.vue";
import Register from "./components/pages/Register.vue";
import AddAnnounce from "./components/pages/AddAnounce.vue";

export default {
  name: "App",
  components: {
    Register,
    HomeVue,
    AddAnnounce,
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
}
@import "~bootstrap/dist/css/bootstrap.css";
</style>
