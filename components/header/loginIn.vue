<template>
  <div class="container">
    <nuxt-link to="/login/index" style="color:#37cab5;">立即登录</nuxt-link>
    <nuxt-link to="/login/index" style="color:#999;">注册</nuxt-link>
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
  }
  .container > a {
    text-decoration: none;
  }
</style>
