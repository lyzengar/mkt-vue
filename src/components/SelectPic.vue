<template>
    <div class="select-pic"></div>
</template>

<script>
export default {
    name: "SelectPic"
}
</script>

<style scoped>
.select-pic {
    display: flex;
    flex-direction: column;
    width: 25%;
    align-items: center;
    border-right: solid white 1px;
    padding-top: 5px;
}

button {
    width: 99%;
    border: none;
    color: white;
    background-color: black;
    padding: 4px;
    font-size: 24px;
    font-family: 'IM Fell DW Pica SC', serif;
}

button:hover, button:focus {
    background-color: #383838;
    outline: none;
    cursor: pointer;
}
</style>