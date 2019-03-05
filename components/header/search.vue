<template>
  <div class="container">
    <div class="img">
      <img src="~/assets/image/logo.png" alt="" />
    </div>
    <div class="search">
      <el-input
        placeholder="请输入内容"
        v-model="input5"
        class="input-with-select"
      >
        <el-button slot="append" icon="el-icon-search"></el-button>
      </el-input>
      <div class="multi">
        <span v-for="item in multiList" :key="item" class="item">{{
          item
        }}</span>
      </div>
    </div>
  </div>
</template>

<script>
  export default {
    components: {},
    data() {
      return {
        input5: "",
        multiList: [
          "世界之窗",
          "深圳欢乐谷",
          "深圳野生动物园",
          "锦绣中华民俗文化村",
          "海上田园",
          "5D星光影错视觉馆"
        ]
      };
    }
  };
</script>

<style scoped>
  .container {
    height: 130px;
    display: flex;
    padding: 40px 200px;
  }
  .container img {
    width: 126px;
    height: 46px;
  }
  .container > .search {
    margin-left: 150px;
    width: 530px;
  }
  .container > .search > .multi {
    font-size: 12px;
    color: #999;
    margin: 10px;
  }
  .container > .search > .multi > .item {
    margin: 0 5px;
  }
</style>
