<template>
    <button type="button" class="btn">{{text}}</button>
</template>

<script>
    export default {
        name: "Button",
        props: {
            text: String
        }
    }
</script>

<style lang="scss" scoped>
    $clr-blue: rgba(1, 90, 159, 1);
    $clr-white: #fff;

    .btn{
        font-size: 16px;
        font-weight: 600;
        background: $clr-blue;
        border: none;
        color: $clr-white;
        padding: 10px 20px;
        height: 40px;
        border-radius: 6px;
        cursor: pointer;
    }
</style>