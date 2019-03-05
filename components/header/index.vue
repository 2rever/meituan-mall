<template>
  <div class="container">
    <div class="up">
          <City class="city"/>
          <Nav />

    </div>
    <div class="down">
      <Search />
    </div>
  </div>
  
</template>

<script>
  import City from "~/components/header/city.vue";
  import Nav from "~/components/header/Nav.vue";
  import Search from "~/components/header/search.vue";
    // import Search from "~/components/header/search.vue";
  export default {
    components: {
        City,
        Nav,
        // Logo,
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
  .down {
    height: 150px;
     padding: 10px 200px;
    background-color: #fff;
    outline: 1px solid lightgreen;
  }
</style>
