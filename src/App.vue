<script>
import Navbar from "./components/Navbar.vue";
import Jumbotron from "./components/JumboTron.vue";
import Contentbar from "./components/Contentbar.vue";
import Footer from "./components/Footer.vue";
import BottomNav from "./components/BottomNav.vue";
export default {
data() {
  return {
    
  }
},

components: {
  Navbar,
  Contentbar,
  Footer,
  BottomNav,
  Jumbotron
}

}
</script>

<template>
  <div>
    <Navbar></Navbar>
    <Jumbotron></Jumbotron>
    <Contentbar></Contentbar>
    <Footer></Footer>
    <BottomNav></BottomNav>
  </div>
</template>

<style lang="scss" scoped>

</style>
