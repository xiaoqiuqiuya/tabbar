<template>
  <div id="app">
    <router-view></router-view>
    <tab-bar>
      <tab-bar-item path="/home" activeColor="#ff99ff">
        <img src="./assets/img/tabbar/home.svg" slot="item-icon" alt />
        <img src="./assets/img/tabbar/home-active.svg" slot="item-icon-active" alt />
        <div slot="item-text">首页</div>
      </tab-bar-item>
      <tab-bar-item path="/category" activeColor="#ff99ff">
        <img src="./assets/img/tabbar/category.svg" slot="item-icon" alt />
        <img
          src="./assets/img/tabbar/category-active.svg"
          slot="item-icon-active"
          alt
        />
        <div slot="item-text">分类</div>
      </tab-bar-item>
      <tab-bar-item path="/cart" activeColor="#ff99ff">
        <img src="./assets/img/tabbar/cart.svg" slot="item-icon" alt />
        <img src="./assets/img/tabbar/cart-active.svg" slot="item-icon-active" alt />
        <div slot="item-text">购物车</div>
      </tab-bar-item>
      <tab-bar-item path="/profile" activeColor="#ff99ff">
        <img src="./assets/img/tabbar/user.svg" slot="item-icon" alt />
        <img src="./assets/img/tabbar/user-active.svg" slot="item-icon-active" alt />
        <div slot="item-text">我的</div>
      </tab-bar-item>
    </tab-bar>
  </div>
</template>

<script>
import TabBar from "./components/tabbar/TabBar";
import TabBarItem from "./components/tabbar/TabBarItem";

export default {
  name: "App",

  components: {
    TabBar,
    TabBarItem,
  },
};
</script>

<style>
@import "./assets/css/base.css";
</style>
