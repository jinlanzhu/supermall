<template>
  <div>
    <tab-bar>
      <tab-bar-item path="/home" activeColor="red">
        <img slot="item-icon" src="./assets/img/tabbar/home.svg" alt="">
        <img slot="item-icon-active" src="./assets/img/tabbar/home_active.svg" alt="">
        <p slot="item-text">首页</p>
      </tab-bar-item>
      <tab-bar-item path="/category" colorStyle="red">
        <img slot="item-icon" src="./assets/img/tabbar/category.svg" alt="">
        <img slot="item-icon-active" src="./assets/img/tabbar/category_active.svg" alt="">
        <p slot="item-text">分类</p>
      </tab-bar-item>
      <tab-bar-item path="/cart" colorStyle="red">
        <img slot="item-icon" src="./assets/img/tabbar/shopcar.svg" alt="">
        <img slot="item-icon-active" src="./assets/img/tabbar/shopcar_active.svg" alt="">
        <p slot="item-text">购物车</p>
      </tab-bar-item>
      <tab-bar-item path="/profile" colorStyle="red">
        <img slot="item-icon" src="./assets/img/tabbar/profile.svg" alt="">
        <img slot="item-icon-active" src="./assets/img/tabbar/profile_active.svg" alt="">
        <p slot="item-text">我的</p>
      </tab-bar-item>

    </tab-bar>
  </div>
</template>

<script>
  import TabBar from "components/common/TabBar"
  import TabBarItem from "components/common/TabBarItem"
  export default {
    name: "MainTabBar",
    components: {
      TabBar,
      TabBarItem
    }
  }
</script>

<style scoped>

</style>
