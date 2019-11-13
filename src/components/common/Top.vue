<template>
    <div class="top">
        <div class="left"></div>
        <div class="center">我的</div>
        <div class="right">
            <div>☼</div>
        </div>
    </div>
</template>

<script>
    export default {
        name: "Top"
    }
</script>

<style scoped>
    .top{
        overflow: auto;
        height: 40px;
        line-height: 40px;
    }
    .top > div{
        float: left;
        width: 33%;
    }
    .left {
        height: 1px;
    }
    .center {
        text-align: center;
        font-size: 1.8em;
    }
    .right > div {
        float: right;
        margin-right: 10px;
    }
</style>