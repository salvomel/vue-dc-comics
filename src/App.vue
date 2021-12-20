<template>
  <div id="app">
    <Header />

    <main></main>

  </div>
</template>

<script>
import Header from "./components/Header.vue";

export default {
  name: "App",
  components: {
    Header,
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
