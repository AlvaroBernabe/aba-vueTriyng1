<template>
    <h1>Simple Formulario</h1>
    <form action="">
        <label for="">Username</label>
        <input type="text" name="" id="" placeholder="username" v-model="form.username" >
        <br>
        <br>
        <label for="">Password</label>
        <input type="text" name="" id="" placeholder="password" v-model="form.password" >

        <br>
        <button v-on:click="login">
            Sign Up
        </button>
        </form>
</template>

<script>
export default {
    name: "Formulario-com",
    data() {
        return {
            form: {
                username: "",
                password: "",
            }
        }
    },
    methods: {
        login() {
            console.table("login data", this.form);
        }
    }
}
</script>

<style>

</style>