<template>
  <div class="home">
    <Header></Header>
    <Search></Search>
    <Footer></Footer>
  </div>
</template>

<script>
  import Header from "./common/Header.vue";
  import Search from "./common/Search.vue";
  import Footer from "./common/Footer.vue";
export default {
  name: "Home",
  data(){
        return {}
      },
      methods:{

      },
      components:{
        Header,
        Footer,
        Search,
      }
}
</script>

<style scoped>

</style>
