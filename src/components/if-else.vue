<template>
    <h1 id="pages2" v-if="display">If Statement</h1>
    <!-- <h1 id="pages3" v-if="show">If else Statement 2</h1> -->
    <h1 id="pages3" v-else>Else Statement </h1>
    <button v-on:click="display = true">Click Button</button>
    <button v-on:click="display = !display">Reset button</button>

</template>

<script>
export default {
    name: "if-else",
    data() {
        return{
            // display: true,
            display: false,
            // show: true,
    }}
}
</script>
<style>
h1 {
    color: red;
}
</style>