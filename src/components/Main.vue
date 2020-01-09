<template>
    <div class="main">
        <SelectPic />
        <Pic />
    </div>
</template>

<script>
import Pic from "./Pic.vue";
import SelectPic from "./SelectPic.vue";

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