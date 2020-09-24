<template>
  <div id="app">
    <tab-bar>
      <tab-bar-item>
        <img src="./assets/img/tabbar/home.png" slot="item-icon" alt />
        <div slot="item-text">首页</div>
      </tab-bar-item>
      <tab-bar-item>
        <img src="./assets/img/tabbar/home.png" slot="item-icon" alt />
        <div slot="item-text">首页</div>
      </tab-bar-item>
      <tab-bar-item>
        <img src="./assets/img/tabbar/home.png" slot="item-icon" alt />
        <div slot="item-text">首页</div>
      </tab-bar-item>
      <tab-bar-item>
        <img src="./assets/img/tabbar/home.png" slot="item-icon" alt />
        <div slot="item-text">首页</div>
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
    TabBarItem
  }
};
</script>

<style>
@import "./assets/css/base.css";
</style>
