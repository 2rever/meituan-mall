<template>
  <div class="container">
    <div class="left"><div class="allItems">全部分类</div></div>
    <div class="right">
      <dt class="lists">
        <dl v-for="item in list" :key="item" class="items">{{ item }}</dl>
      </dt>
    </div>
  </div>
</template>

<script>
  export default {
    components: {},
    data() {
      return {
        list: [
          "美团外卖",
          "猫眼电影",
          "美团酒店",
          "民宿/公寓",
          "商家入驻",
          "美团公益"
        ]
      };
    }
  };
</script>

<style scoped>
  .container {
    height: 50px;
    display: flex;
    padding: 0 200px;
    vertical-align: middle;
    box-shadow: 10px 5px 5px rgba(0, 0, 0, 0.1);
  }
  .container > .left {
    width: 230px;
    background-color: #51c0ad;
    color: #fff;
  }
  .container > .left > .allItems {
    padding: 10px 10px;
  }
  .container > .right {
    margin-left: 40px;
  }
  .right > .lists {
    display: flex;
  }
  .items {
    font-weight: 700;
    margin: 10px 20px;
  }
</style>
