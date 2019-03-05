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
    </div>
  </div>
</template>

<script>
  export default {
    components: {},
    data() {
      return {
        input5: ""
      };
    }
  };
</script>

<style scoped>
  .container {
    display: flex;
  }
  .container img {
    width: 126px;
    height: 46px;
  }
  .container > .search {
    margin-left: 150px;
    width: 400px;
  }
</style>
