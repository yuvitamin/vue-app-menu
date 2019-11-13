<template>
    <div class="home">
        <menus></menus>
        <menus2></menus2>
    </div>
</template>

<script>
    import Menus from "./home/Menus";
    import Menus2 from "./home/Menus2";
    export default {
        name: "Home",
        components: {
            Menus,
            Menus2
        }
    }
</script>

<style scoped>

</style>