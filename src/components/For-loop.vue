<template>
    <h1>For loop</h1>
    <ul>
        <li v-for="program in technology" :key="program">
            {{ program }}
        </li>
    </ul>
    <br>
    <ul>
        <li v-for="data in user" :key="data">
            Name is: {{ data.name }}
        </li>
        <li v-for="data in user" :key="data">
            Email is: {{ data.email }}
        </li>
        <li v-for="data in user" :key="data">
            Number is: {{ data.number }}
        </li>
    </ul>
</template>

<script>
export default {
    name: 'forLoop',
    data() {
        return {
            technology: ["PHP", "JavaScript", "C++", "C-sharp"],
            user: [{
                name: "Jack",
                email: "jack@email.com",
                number: 666555889,
            },
            {
                name: "Erick",
                email: "Erick@email.com",
                number: +348833221,
            },
            ]
        }
    }
}
</script>

<style>
h1 {
    color: blueviolet;
}
</style>