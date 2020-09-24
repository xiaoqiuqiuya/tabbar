<template>
    <div class="tab-bar-item">
      <!-- <img src="../../assets/img/tabbar/home.png" alt="">
      <div>首页</div> -->
      <slot name="item-icon"></slot>
      <slot name="item-text"></slot>
    </div>
</template>

<script>
export default {};
</script>

<style>


.tab-bar-item {
  flex: 1;
  text-align: center;
  height: 49px;
  font-size: 14px;
}
.tab-bar-item img {
  height: 24px;
  width: 24px;
}
</style>