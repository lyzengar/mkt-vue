<template>
  <div id="app">
    <NavBar />
    <Main />
    <!-- <img alt="Vue logo" src="./assets/logo.png" />
    <HelloWorld msg="Welcome to Your Vue.js App" /> -->
  </div>
</template>

<script>
// import HelloWorld from "./components/HelloWorld.vue";
import NavBar from "./components/NavBar.vue";
import Main from "./components/Main.vue";
export default {
  name: "app",
  components: {
    NavBar,
    Main,
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
  font-family: 'IM Fell DW Pica SC', serif;
}
</style>
