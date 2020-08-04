<template>
  <div id="tab-bar">
   <slot>

   </slot>

  </div>
</template>

<script>
  export default {
    name: "TabBar"
  }
</script>

<style scoped>
  #tab-bar {
    left: 0;
    right: 0;
    bottom: 0;
    height: 49px;
    display: flex;
    font-size: 14px;
    text-align: center;
    position: absolute;
    background: #f3f3f3;
    box-shadow: 0px -1px 2px rgba(100, 100, 100, 0.1);
  }
  .tab-bar-item {
    flex: 1;
  }
  .tab-bar-item img {
    width: 24px;
    height: 24px;
    margin-top: 3px;
    vertical-align: center;
  }
</style>
