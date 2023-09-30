<template>
    <ul>
        <li v-for="item in users" :key="item.name">
            <NewUser :data="item" />
        </li>
    </ul>
    <div v-html="emailadresss"></div>
    <h1 v-html="id"></h1>

    <!-- <NewUser /> -->
</template>

<script>
import NewUser from "./new-user.vue";
export default {
    name: "child-components",
    props: {
        name: String,
        user: Object,
        getData: Function
    },
    data() {
        return {
            // users: [
            //     {
            //         name: "jacson",
            //         email: "jackson@email.com",
            //     },
            //     {
            //         name: "juan",
            //         email: "juan@email.com",
            //     },
            //     {
            //         name: "paco",
            //         email: "paco@email.com",
            //     },
            //     {
            //         name: "federico",
            //         email: "federico@email.com",
            //     },
            // ]
            anmes: "peter",
            emailadresss: "<h1>peter@gmail.com</h1>",
            id: 895641513,
        }
    },
    components: { NewUser },
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
