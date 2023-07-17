<template>
    <button class="btn" :style="{background:color}">{{text}}</button>
</template>

<script>
export default {
    name: 'ButtonComponent',
    props: {
        text: String,
        color:String
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
    padding: 10px 12px;
}
</style>
