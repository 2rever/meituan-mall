<template>
  <div class="container">
    <div class="city">
      <i class="el-icon-location icon"></i>
      <span>深圳</span>
      <button class="cityChange">切换城市</button>
      <span class="nearCity">[ 东方 基隆 嘉义市 ]</span>
    </div>
    <div class="login">
      <nuxt-link to="~/pages/login" style="color:#37cab5;">立即登录</nuxt-link>
      <nuxt-link to="" style="color:#999;">注册</nuxt-link>
    </div>
  </div>
</template>

<script>
  export default {
    components: {}
  };
</script>

<style scoped>
  .container {
    font-size: 12px;
    display: flex;
    vertical-align: text-bottom;
  }
  .container > .city > .icon {
    color: #999;
  }
  .container > .city > .cityChange {
    box-sizing: border-box;
    font-size: 12px;
    padding: 0;
    border: 1px solid #eee;
    background-color: #f4f4f4;
  }
  .container > .city > .nearCity {
    color: #999;
  }
  .container > .login {
    margin-left: 20px;
  }
  .container > .login > a {
    text-decoration: none;
  }
</style>
