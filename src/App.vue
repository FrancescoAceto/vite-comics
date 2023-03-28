<script>
import Navbar from "./components/Navbar.vue";
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
}

}
</script>

<template>
  <div>
    <Navbar></Navbar>
    <Contentbar></Contentbar>
    <Footer></Footer>
    <BottomNav></BottomNav>
  </div>
</template>

<style lang="scss" scoped>

</style>
