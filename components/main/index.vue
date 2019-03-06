<template>
  <div class="container">
   <Menus />
  <MenusCards />
  </div>
</template>

<script>
  import Menus from "~/components/main/menus.vue";
  import MenusCards from "~/components/main/menusCards.vue";

  export default {
    components: {Menus,MenusCards},
    data() {
      return {};
    }
  };
</script>

<style scoped>
  .container {
    display: flex;
    padding: 0 200px;
  }
</style>
