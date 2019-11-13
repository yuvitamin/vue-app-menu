<template>
  <div>
    <ScopeParentSlot></ScopeParentSlot>
    <top></top>
    <home></home>
    <bottom></bottom>

  </div>
</template>

<script>


  import Top from "./components/common/Top";
  import Home from "./components/Home";
  import Bottom from "./components/common/Bottom";


  export default {
    name: 'app',
    components: {
      Bottom,
      Home,
      Top,
    }
  };
</script>

<style>
</style>
