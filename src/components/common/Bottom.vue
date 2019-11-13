<template>
    <div class="footer">
        <div class="footer-f">
            <div>首页</div>
        </div>
        <div class="footer-c">
            <div>消息</div>
        </div>
        <div class="footer-l">
            <div>我的</div>
        </div>
    </div>
</template>

<script>
    export default {
        name: "Bottom"
    }
</script>

<style scoped>

    .footer {
        width: 100%;
        position: fixed;
        bottom: 0;
        overflow: auto;
        border-top: #f0f0f0 solid 1px;
        height: 50px;
        line-height: 50px;
    }

    .footer > div {
        float: left;
        width: 33%;
        font-size: 1.5em;
    }

    .footer-f {

    }

    .footer-f div {
        margin-left: 15px;
    }

    .footer-c {
        text-align: center;
    }

    .footer-l {
        text-align: right;
    }

    .footer-l div {
        margin-right: 10px;
    }
</style>