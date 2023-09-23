<template>
    <h1>Hello{{ 10 + 10 }}</h1>
    <h2>{{ "hello".length }}</h2>
    <h2>email: {{ email }}</h2>
    <h2>telefono: {{ mobile }}</h2>
    <!-- <h2>telefono: {{ mobile = 999 }}</h2> -->
    <h2>telefono: {{ mobile == 999 }}</h2>
    <h2>nombre: {{ getName1 }}</h2>
    <h2>nombre: {{ getName1() }}</h2>
    <h2>{{getData()}}</h2>
</template>

<script>
export default {
    name: "PAGES",
    // email: "ejemplo@email.com",
    data() {
        return {
            email: "ejemplo@email.com",
            mobile: "66644455587",
            // getName1: function() {
            //     return "me lamo Alvaro";
            // },
        };
    },
    methods: {
        getName1: function () {
            return "me lamo Alvaro";
        },
        getName(Name) {
            return Name;
        },
        getData() {
            return {
                email: this.email,
                mobile: this.mobile
            };
        },
    },
};
</script>
<style scoped>
h1 {
    color: red;
}

h2 {
    color: blue;
}
</style>