<template>
    <h1>Hello{{ 10 + 10 }}</h1>
    <h2>{{ "hello".length }}</h2>
    <h2>email: {{ email }}</h2>
    <h2>telefono: {{ mobile }}</h2>
    <!-- <h2>telefono: {{ mobile = 999 }}</h2> -->
    <!-- <h2>telefono: {{ mobile == 999 }}</h2>
    <h2>nombre: {{ getName1 }}</h2>
    <h2>nombre: {{ getName1() }}</h2> -->
    <!-- <h2>{{getData()}}</h2> -->
    <button v-on:click="ejemplo1()">Boton 1</button>
    <button v-on:click="ejemplo2()">Boton 2</button>
    <button v-on:dblclick="ejemplo3()">Boton Doble click</button>
    <!-- <h1 v-on:mousemove="getConsole('')">Home Page</h1> Esto funciona cuando el ratón este encima -->
    <h1 v-on:mousemove="getConsole('')">Home Page</h1> 

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
            ejemplo1() {console.log("Has pulsado el boton correctamente")},
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
        ejemplo2() {
            alert("Has pulsado el Botón II")
        },
        ejemplo3() {
            alert("Has pulsado el Botón 3")
        },
        // getConsole() {
        //     console.error("Function is running")
        // },
        getConsole() {
            console.warn("Function is running")
        }
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