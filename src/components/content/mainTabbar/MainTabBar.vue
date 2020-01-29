<template>
  <tab-bar>
    <tab-bar-item path="/home" active-color="red">
      <img slot="item-icon" src="~assets/img/tabbar/home.jpg" alt="">
      <img slot="item-icon-active" src="~assets/img/tabbar/home_active.jpg" alt="">
      <div slot="item-text">首页</div>
    </tab-bar-item>
    <tab-bar-item path="/category" active-color="red">
      <img slot="item-icon" src="~assets/img/tabbar/category.jpg" alt="">
      <img slot="item-icon-active" src="~assets/img/tabbar/category_active.jpg" alt="">
      <div slot="item-text">分类</div>
    </tab-bar-item>
    <tab-bar-item path="/cart">
      <img slot="item-icon" src="~assets/img/tabbar/cart.jpg" alt="">
      <img slot="item-icon-active" src="~assets/img/tabbar/cart_active.jpg" alt="">
      <div slot="item-text">购物车</div>
    </tab-bar-item>
    <tab-bar-item path="/profile" active-color="red">
      <img slot="item-icon" src="~assets/img/tabbar/profile.jpg" alt="">
      <img slot="item-icon-active" src="~assets/img/tabbar/profile_active.jpg" alt="">
      <div slot="item-text">我的</div>
    </tab-bar-item>
  </tab-bar>
</template>

<script>
  import TabBar from "./tabbar/TabBar";
  import TabBarItem from "./tabbar/TabBarItem";

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
