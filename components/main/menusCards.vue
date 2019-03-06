<template>
  <div class="menusCardss">
    <div class="ups">
      <div class="swiper">
        <el-carousel trigger="click" height="240px" width="550px;">
          <el-carousel-item v-for="(item,index) in bannerList" :key="index">
            <a href="/"><img :src="item"/></a>
          </el-carousel-item>
        </el-carousel>
      </div>
      <span>
        <img
          height="240px;"
          width="150px;"
          src="http://p0.meituan.net/codeman/e473bb428f070321269b23370ff02ba956209.jpg"
          alt=""
        />
      </span>
    </div>
  </div>
</template>

<script>
  export default {
    components: {},
    data() {
      return {
        bannerList: [
          "http://p0.meituan.net/codeman/daa73310c9e57454dc97f0146640fd9f69772.jpg",
          "http://p1.meituan.net/codeman/826a5ed09dab49af658c34624d75491861404.jpg",
          "http://p0.meituan.net/codeman/33ff80dc00f832d697f3e20fc030799560495.jpg"
        ]
      };
    }
  };
</script>

<style scoped>
  .menusCardss > .ups {
    font-size: 0;
    display: flex;
  }
  .swiper {
    height: 240px;
    width: 550px;
  }
  .swiper img {
    width: 100%;
    height: 100%;
  }
  .up {
    padding: 10px 0 0 10px;
  }
  .up > .cards {
    margin-left: 10px;
  }
  .imgss img {
    width: 150px;
    height: 240px;
  }
</style>
