<template>
    <div>
        <div class="my-list-hr"></div>

        <ul v-for="(list, index) in lists" :key="index">
            <li v-for="menu in list" :key="menu.id" id="li">
                <div class="my-list">
                    <div v-text="menu.title"></div>
                    <div class="right">></div>
                </div>
            </li>
            <div v-if="index < lists.length - 1" class="my-list-hr"></div>
        </ul>
    </div>
</template>

<script>
    export default {
        name: "Menus2",
        data() {
            return {
                lists: [
                    [
                        {id: 1, title: "我的订单", url: ""}
                    ],
                    [
                        {id: 2, title: "我的发布", url: ""},
                        {id: 3, title: "我的收藏", url: ""},
                        {id: 4, title: "我的小区", url: ""}
                    ],
                    [
                        {id: 5, title: "我的报修", url: ""},
                        {id: 6, title: "用户反馈", url: ""},
                        {id: 7, title: "关于我们", url: ""}
                    ]
                ]
            }
        }
    }
</script>

<style scoped>

    .my-list {
        margin-left: 15px;
        border-bottom: #f0f0f0 solid 1px;
        overflow: auto;
        height: 40px;
        line-height: 30px;
        color: slategray;
    }

    .my-list > div {
        float: left;
    }

    .my-list .right {
        float: right;
        margin-right: 10px;
    }

    .my-list-hr {
        height: 10px;
        background-color: #f0f0f0;
    }


    #li {
        list-style: none;
    }
</style>