<template>
    <h1>How to add input boxes in multiple binding</h1>
    <label for="cricket">Cricket</label>
    &nbsp;
    <input type="checkbox">
    <br />
    <label for="bootball">Football</label>
    &nbsp;
    <input type="checkbox">
    <br />
    <label for="hockey">Hockey</label>
    &nbsp;
    <input type="checkbox">
    <h3>Selected Sport</h3>
</template>

<script>
export default {
    name: "inputBoxes",
    data() {
        return{
            count: 20
    }}
}
</script>

<style>
h1 {
    color: green;
}
</style>