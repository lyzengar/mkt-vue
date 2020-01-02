<template>
    <div class="main">
        <Pic />
    </div>
</template>

<script>
import Pic from "./components/Pic.vue";

export default {
    name: "Main",
    components: {
        Pic
    }
}
</script>

<style scoped>
    .main {
        display: flex;
    }
</style>