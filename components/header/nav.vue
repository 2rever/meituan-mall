<template>
  <div class="container">
    <div v-for="item in list" :key="item" class="item">{{ item }}</div>
  </div>
</template>

<script>
  export default {
    components: {},
    data() {
      return {
        list: ["我的美团", "手机APP", "商家中心", "网站导航"]
      };
    }
  };
</script>

<style scoped>
  .container {
    display: flex;
    font-size: 12px;
    color: #999;
  }
  .container .item {
    padding: 0 16px;
  }
</style>
