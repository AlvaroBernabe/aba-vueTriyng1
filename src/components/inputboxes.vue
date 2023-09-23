<template>
    <h1>How to add input boxes in multiple binding</h1>
    <label for="cricket">Cricket</label>
    &nbsp;
    <input type="checkbox" value="Cricket" v-model="sport">
    <br />
    <label for="football">Football</label>
    &nbsp;
    <input type="checkbox" value="Football" v-model="sport">
    <br />
    <label for="hockey">Hockey</label>
    &nbsp;
    <input type="checkbox" value="Hockey" v-model="sport">
    <br>
    <h3>Selected Sport: {{ sport }}</h3>
    <h3>Selected Player: {{ player }}</h3>

    <label for="playerName">Player Name:</label>
    &nbsp; &nbsp;

    <label for="">Smith</label>
    <input type="radio" value="Smith" name="name" id="name" v-model="player">

    <label for="">Fich</label>
    <input type="radio" value="Fich" name="name" id="name2" v-model="player">
    <br>
</template>

<script>
export default {
    name: "inputBoxes",
    data() {
        return{
            sport: [],
            player: []
    }}
}
</script>

<style>
h1 {
    color: green;
}
</style>