<template>
    <div class="nav-bar">
        <div class="nav-head">
            <h2>Makoto Taiko Equipment</h2>
            <h2>真鼓音</h2>
        </div>
        <div class="nav-sections">
            <h3>Taiko</h3>
            <h3>Stands</h3>
            <h3>Misc.</h3>
        </div>
    </div>
</template>

<script>
export default {
  name: "NavBar",
  props: {

  }
};
</script>

<style scoped>
    @import url('https://fonts.googleapis.com/earlyaccess/sawarabimincho.css');
    .nav-bar {
        border-bottom: solid white 1px;
    }
    .nav-head {
        display: flex;
        justify-content: space-between;
        padding: 0 20px;
        margin-bottom: -30px;
        line-height: 1.0;
    }
    .nav-head h2:nth-child(2) {
        font-family: "Sawarabi Mincho";
    } 
    .nav-sections {
        display: flex;
        justify-content: center;
    }
    h2 {
    font-size: 34px;
    }
    h3 {
        padding: 0 40px;
        font-size: 24px;
    }
    h3:hover {
        background-color: #383838;
        cursor: pointer;
    }
</style>