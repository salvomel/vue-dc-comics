<template>
  <div id="app">
    <Header />

    <main></main>

    <Prefooter />

    <Footer />

  </div>
</template>

<script>
import Header from "./components/Header.vue";
import Footer from "./components/Footer.vue";
import Prefooter from "./components/Prefooter.vue";

export default {
  name: "App",
  components: {
    Header,
    Footer,
    Prefooter
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
