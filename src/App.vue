<template>
  <Header />
  <Menu />
  <Footer />
</template>
<script>
import Header from "./components/layout/Header.vue";
import Menu from "./components/Menu.vue";
import Footer from "./components/layout/Footer.vue";

export default {
  name: "App",
  components: {
    Header,
    Menu,
    Footer,
  },
};
</script>
