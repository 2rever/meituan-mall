<template>
  <div class="container">
  <Header />
  <Main />
  <Footer />
  </div>
    
</template>

<script>
  import Footer from "~/components/footer/index.vue";
   import Main from "~/components/main/index.vue";
  import Header from "~/components/header/index.vue";

  export default {
    components: {
      Header,
      Main,
      Footer
    }
  };
</script>

<style>

</style>
