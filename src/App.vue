<template>
  <div id="app">
    <!-- <NavigationBar /> -->
    <HelloWorld msg="Welcome to Your Vue.js App" />
  </div>
</template>

<script>
import HelloWorld from "./components/HelloWorld.vue";
import NavigationBar from "./components/NavigationBar.vue";

export default {
  name: "App",
  components: {
    HelloWorld,
    NavigationBar,
  },
};
</script>

