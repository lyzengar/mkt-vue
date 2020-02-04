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

var taiko = {
          a: {menu: "Asano", caption: "A1, A2, A3", URL: "https://imgur.com/Ajzm4Jh.jpg"},
          b: {menu: "Small Asano", caption: "As1, As2", URL: "https://imgur.com/oBr47Rn.jpg"},
          c: {menu: "Kato", caption: "K1, K2", URL: "https://imgur.com/o059u7P.jpg"},
          d: {menu: "Heavy", caption: "H", URL: "https://imgur.com/OJZPxEP.jpg"},
          e: {menu: "Red", caption: "Red", URL: "https://imgur.com/WozGHYJ.jpg"},
          f: {menu: "Black and Red", caption: "BR", URL: "https://imgur.com/pQtG99L.jpg"},
          g: {menu: "Crestone 1", caption: "C1", URL: "https://imgur.com/rMDKk4x.jpg"},
          h: {menu: "Crestone 2", caption: "C2", URL: "https://imgur.com/R0z9RgX.jpg"},
          i: {menu: "Crestone 3", caption: "C3", URL: "https://imgur.com/RFkynuP.jpg"},
          j: {menu: "Big Dana", caption: "", URL: "https://imgur.com/BEDGpGu.jpg"},
          k: {menu: "Masala", caption: "", URL: "https://imgur.com/HqGtMdG.jpg"},
          l: {menu: "Shime", caption: "San-cho 2x, Regular 4x", URL: "https://imgur.com/tW2lxfH.jpg"},
          m: {menu: "Odaiko", caption: "w/ stand", URL: "https://imgur.com/YONMJcc.jpg"},
          n: {menu: "Okedo", caption: "", URL: "https://imgur.com/lMCiHaK.jpg"}
};

var stands = {
          a: {menu: "Box Stand", caption: "", URL: "https://imgur.com/UbLw9dU.jpg"},
          b: {menu: "Kato Stand", caption: "", URL: "https://imgur.com/u6Mstzr.jpg"},
          c: {menu: "Yatai Stand (Asano)", caption: "", URL: "https://imgur.com/mwvfEdc.jpg"},
          d: {menu: "Yatai Stand (black)", caption: "", URL: "https://imgur.com/OMGqRZu.jpg"},
          e: {menu: "Hachijo Stand", caption: "", URL: "https://imgur.com/tJEJErD.jpg"},
          f: {menu: "High Stand", caption: "", URL: "https://imgur.com/EcFS4Oq.jpg"},
          g: {menu: "Odaiko Stand (beta)", caption: "", URL: "https://imgur.com/HEiEAyQ.jpg"},
          h: {menu: "Shime Stand (sitting)", caption: "", URL: "https://imgur.com/WqmRzzv.jpg"},
          i: {menu: "Shime Stand (standing)", caption: "", URL: "https://imgur.com/oi5O7zW.jpg"},
          j: {menu: "Okedo Stand", caption: "", URL: "https://imgur.com/mODhyVr.jpg"},
          k: null,
          l: null,
          m: null,
          n: null
}

var percussion = {
          a: {menu: "Tetsuzutsu", caption: "Tetsuzutsu (cannon)", URL: "https://imgur.com/atpRlwT.jpg"},
          b: {menu: "Kane", caption: "", URL: "https://imgur.com/KCeNuGs.jpg"},
          c: null,
          d: null,
          e: null,
          f: null,
          g: null,
          h: null,
          i: null,
          j: null,
          k: null,
          l: null,
          m: null,
          n: null

};

var vm = new Vue ({
  data: taiko
})

handleTaiko = () => {
  
}
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
