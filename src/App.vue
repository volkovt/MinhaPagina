<template>
  <div class="main">
    <NavBar class="app-nav" />
    <div class="app-body">
      <router-view></router-view>
    </div>
    <Footer class="footer" />
  </div>
</template>

<script>
import NavBar from "@/components/NavBar";
import Footer from "@/components/Footer.vue";

export default {
  components: { NavBar, Footer },
};
</script>

<style lang="scss">
.main {
  height: 100vh;
  display: flex;
  flex-direction: column;

  .app-nav {
    flex: 1;
    background-color: rgb(48, 31, 59);
  }

  .app-body {
    flex: 10;
  }

  .app-footer {
    flex: 1;
  }
}
</style>
