<template>
  <!-- 顶部的搜索栏 -->
  <div class="index">
    <div class="nav">
      <input
        type="text"
        placeholder="搜索"
      >
    </div>
  </div>
</template>
<script>
export default {};
</script>

<style lang="scss">
// 定义变量
$uRed: #ff2d4a;
.nav {
  padding: 20rpx 16rpx;
  background-color: $uRed;
  input {
    background-color: white;
    height: 60rpx;
    text-align: center;
    color: #bbb;
    font-size:24rpx;
  }
}
</style>
