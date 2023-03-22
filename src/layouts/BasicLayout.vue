<template>
  <div>
    <Header />
    <Footer />
    <div class="layout">
      <router-view></router-view>
    </div>
    <SiderMenu />
  </div>
</template>

<script>
import Header from "./Header.vue";
import Footer from "./Footer.vue";
import SiderMenu from "./SiderMenu.vue";
export default {
  components: {
    Header,
    Footer,
    SiderMenu,
  },
};
</script>
<style></style>
