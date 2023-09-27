<template>
    <h1>For loop</h1>
    <ul>
        <li v-for="program in technology" :key="program">
            {{ program }}
        </li>
    </ul>
    <br>
    <ul v-if="Array.isArray(user)">
        <li v-for="data in user" :key="data.email">
            Name is: {{ data.name }}
            Email is: {{ data.email }}
            Number is: {{ data.number }}
        </li>
    </ul>
    <child :name="user.name" :user="user.email" :getData="getData"/>
</template>

<script>
import child from './child.vue';

export default {
    name: 'forLoop',
    data() {
        return {
            technology: ["PHP", "JavaScript", "C++", "C-sharp"],
            user: {
                name: "Tony",
                email: "tony@email.com"
            }
        }
    },
    methods: {
        getData() {
            alert("Methods called")
        }
    },
    components: {child},
}
</script>

<style>
h1 {
    color: blueviolet;
}
</style>
