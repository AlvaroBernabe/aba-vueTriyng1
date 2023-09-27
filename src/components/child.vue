<template>
    <h1>child components</h1>
    <h3>{{ name }}</h3>
    <h3>{{ user }}</h3>
    <button v-on:click="getData()">
        Call the Function
    </button>    
</template>

<script>
export default {
    name: "child-components",
    props: {
        name: String,
        user: Object,
        getData: Function
    },
};
</script>

<style>
h1 {
    color: red;
}
h3 {
    color: blue;
    font-weight: bold;
}
</style>
