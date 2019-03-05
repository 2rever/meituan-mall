<template>
  <div class="container">
  <Header />
  <Footer />
  </div>
    
</template>

<script>
  import Footer from "~/components/footer/index.vue";
  import Header from "~/components/header/index.vue";

  export default {
    components: {
      Header,
      Footer
    }
  };
</script>

<style>

</style>
