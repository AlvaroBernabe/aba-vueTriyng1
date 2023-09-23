<template>
    <h1>Two Way Binding</h1>
    <input type="text" placeholder="Add the number" v-model="count"/>
    <h3>{{ count }}</h3>
</template>

<script>
export default {
    name: "pages-one",
    data() {
        return{
            count: 20
    }}
}
</script>
<style>
h1 {
    color: red;
}
</style>