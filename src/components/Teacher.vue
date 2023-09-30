<template>
    <h1>Teacher Name: {{ name }}</h1>
    <Teacher />
    <Student />
</template>

<script>
export default {
    name: "Teacher-com",
    props: {
        name: String,
    },
};
</script>

<style>

</style>