<template>
  <div id="app">
    <Header />

    <Banner />

    <main></main>

    <Prefooter />

    <Footer />

  </div>
</template>

<script>
import Header from "./components/Header.vue";
import Footer from "./components/Footer.vue";
import Prefooter from "./components/Prefooter.vue";
import Banner from "./components/Banner.vue";

export default {
  name: "App",
  components: {
    Header,
    Footer,
    Prefooter,
    Banner
  },
};
</script>

<style lang="scss">
@import './style/common.scss';
@import './style/general.scss';

main {
  // TEST
  height: 100px;
  background-color: black;
}
</style>
