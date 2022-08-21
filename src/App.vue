<template>
  <Header />
  <router-view />
</template>
<script>
import Header from "./components/HeaderStore.vue";
export default {
  components: {
    Header,
  },
};
</script>
<style>
@import url("https://fonts.googleapis.com/css?family=Exo+2");
#app {
  background-color: #f8f8f8 !important;
  font-family: "Exo 2", sans-serif !important;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  color: #2c3e50;
}
</style>
