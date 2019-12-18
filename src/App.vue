<template>
  <div id="app">
    <NavBar />
    <!-- <img alt="Vue logo" src="./assets/logo.png" />
    <HelloWorld msg="Welcome to Your Vue.js App" /> -->
  </div>
</template>

<script>
// import HelloWorld from "./components/HelloWorld.vue";
import NavBar from "./components/NavBar.vue";
export default {
  name: "app",
  components: {
    NavBar,
    // HelloWorld
  }
};
</script>

<style>
@import url('https://fonts.googleapis.com/css?family=IM+Fell+DW+Pica+SC');
body {
  margin: 0;
}
#app {
  background-color: black;
  color: white;
  margin-bottom: -30px;
  line-height: 1.0;
  font-family: 'IM Fell DW Pica SC', serif;
}
</style>
