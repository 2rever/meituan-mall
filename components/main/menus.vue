<template>
  <div class="menus">
    <dd class="menusLists">
      <dl v-for="item in menuList" :key="item" class="menusList">
        <a href="">{{ item }}</a> <span class="icon">></span>
      </dl>
    </dd>
  </div>
</template>

<script>
  export default {
    components: {},
    data() {
      return {
        menuList: [
          "美食",
          "外卖",
          "酒店",
          "榛果民宿",
          "猫眼电影",
          "机票/火车票",
          "休闲娱乐/KTV",
          "生活服务",
          "丽人/美发/医学美容",
          "结婚/婚纱摄影/婚宴",
          "亲子/儿童乐园/幼教",
          "运动健康/健身中心",
          "家装/建材/家居",
          "学习培训/音乐培训",
          "医疗健康/宠物/爱车",
          "酒吧/密室逃脱"
        ]
      };
    }
  };
</script>

<style scoped>
  .menus {
    color: #fff;
  }
  .menusLists {
    width: 230px;
    background-color: #5ec1ae;
  }
  .menusList {
    display: flex;
    justify-content: space-between;
    font-size: 14px;
    height: 26px;
    padding: 2px 12px;
    box-sizing: border-box;
  }
  .menusList > a {
    color: #fff;
    text-decoration: none;
  }
  .menusList:hover {
    background-color: #7ec8bf;
  }
</style>
