<template>
  <div class="container">
    <div class="up">
          <City class="city"/>
          <Nav />

    </div>
    <div class="middle">
      <Search />
    </div>
    <div class="down">
      <Menu />
    </div>
  </div>
  
</template>

<script>
  import City from "~/components/header/city.vue";
  import Nav from "~/components/header/Nav.vue";
  import Search from "~/components/header/search.vue";
    import Menu from "~/components/header/menu.vue";
  export default {
    components: {
        City,
        Nav,
        Menu,
        Search
   }
  }
</script>

<style scoped>
  .up { 
    display: flex;
    justify-content: space-between;
    padding: 10px 200px;
    height: 40px;
    background-color: #f8f8f8;
  }
  .middle {
    /* height: 150px; */
     /* padding: 10px 200px; */
    /* background-color: #fff; */
   
    /* outline: 1px solid lightgreen; */
  }
  .down {
  /* box-shadow: 0 2px 27px 0 rgba(0,0,0,.1) */
  }
</style>
