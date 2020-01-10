<template>
  <div id="app">
    <NavBar />
    <Main />
    <!-- <HelloWorld msg="Welcome to Your Vue.js App" /> -->
  </div>
</template>

<script>
import NavBar from "./components/NavBar.vue";
import Main from "./components/Main.vue";
export default {
  name: "app",
  components: {
    NavBar,
    Main,
  }
};

let taiko = [
          {menu: "Asano", caption: "A1, A2, A3", URL: "https://imgur.com/Ajzm4Jh.jpg"},
          {menu: "Small Asano", caption: "As1, As2", URL: "https://imgur.com/oBr47Rn.jpg"},
          {menu: "Kato", caption: "K1, K2", URL: "https://imgur.com/o059u7P.jpg"},
          {menu: "Heavy", caption: "H", URL: "https://imgur.com/OJZPxEP.jpg"},
          {menu: "Red", caption: "Red", URL: "https://imgur.com/WozGHYJ.jpg"},
          {menu: "Black and Red", caption: "BR", URL: "https://imgur.com/pQtG99L.jpg"},

        ];
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
