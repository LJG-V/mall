<template>
  <tab-bar>
    <tab-bar-item path="/home">
      <template v-slot:item-icon>
        <img src="../../assets/img/tabbar/home.svg" alt="">
      </template>
      <template v-slot:item-icon-active>
        <img src="../../assets/img/tabbar/home_active.svg" alt="">
      </template>
      <template v-slot:item-text>
        <p>首页</p>
      </template>
    </tab-bar-item>
    <tab-bar-item path="/category">
      <template v-slot:item-icon>
        <img src="../../assets/img/tabbar/category.svg" alt="">
      </template>
      <template v-slot:item-icon-active>
        <img src="../../assets/img/tabbar/category_active.svg" alt="">
      </template>
      <template v-slot:item-text>
        <p>分类</p>
      </template>
    </tab-bar-item>
    <tab-bar-item path="/cart">
      <template v-slot:item-icon>
        <img src="../../assets/img/tabbar/category.svg" alt="">
      </template>
      <template v-slot:item-icon-active>
        <img src="../../assets/img/tabbar/category_active.svg" alt="">
      </template>
      <template v-slot:item-text>
        <p>购物车</p>
      </template>
    </tab-bar-item>
    <tab-bar-item path="/profile">
      <template v-slot:item-icon>
        <img src="../../assets/img/tabbar/profile.svg" alt="">
      </template>
      <template v-slot:item-icon-active>
        <img src="../../assets/img/tabbar/profile_active.svg" alt="">
      </template>
      <template v-slot:item-text>
        <p>我的</p>
      </template>
    </tab-bar-item>
  </tab-bar>
</template>

<script>
  import TabBar from "/common/tabbar/TabBar";
  import TabBarItem from "/common/tabbar/TabBarItem";

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