<template>
    <!-- <h2>New user component</h2> -->
    <div class="usercomponent">
        <h2> {{ data.name }}</h2>
        <h2> {{ data.email }}</h2>
    </div>
</template>

<script>
export default {
    name: "NewUser",
    props:{
        data: Object,
    }, 
};
</script>

<style>
h2 {
    color: blueviolet;
    font-weight: bold;
}
*{
    list-style-type: none;
}
.usercomponent {
    padding: 12px;
    margin-bottom: 15px;
    border: 1px solid;
    background-color: blanchedalmond;
}
</style>
