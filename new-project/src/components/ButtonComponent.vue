<template>
    <button class="btn">{{ text }}</button>
</template>

<script>
export default {
    name: 'ButtonComponent',
    props: {
        text: String,
        color: String
    }
}
</script>

<style>
.btn {
    color: white;
    background-color: grey;
    border: 1px soid black;
    border-radius: 10px;
    font-family: Arial, Helvetica, sans-serif;
    font-weight: 600;
    padding: 10px 16px;
    background-color: rgb(25, 188, 134);
    margin-right: 10px;
}

.btn:hover {

    background-color: aqua;
}
</style>
