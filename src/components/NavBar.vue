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
    .nav-bar {
        display: flex;
        justify-content: space-between;
    }
</style>