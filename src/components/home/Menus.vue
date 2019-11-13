<template>
    <div>
        <div class="menus">
            <div class="left">
                <div><img src="../../assets/logo.png" alt="头像无法加载" class="pic"/></div>
            </div>
            <div class="center">
                <div>
                    <div class="name">我的小区</div>
                    <div class="addresses">金国际城</div>
                </div>
            </div>
            <div class="right">
                <div>
                    <div class="right-img">></div>
                </div>
            </div>
        </div>
    </div>
</template>

<script>
    export default {
        name: "Menus"
    }
</script>

<style scoped>

    .menus {
        overflow: auto;
        height: 80px;
        background-color: #ffbe26;
    }

    .menus > div {
        float: left;
        width: 33%;
    }

    .menus .left > div {
        margin-left: 50px;
    }

    .pic {
        margin-top: 15px;
        width: 50px;
        height: 50px;
    }

    .menus .center {
        color: aliceblue;
        text-align: center;
    }

    .name {
        margin-top: 13px;
        font-size: 20px;
    }

    .addresses {
        font-size: 13px;
    }


    .menus .right {
        text-align: right;
    }

    .right-img {
        color: aliceblue;
        font-size: 45px;
        margin-top: 5px;
        margin-right: 5px;
    }

</style>