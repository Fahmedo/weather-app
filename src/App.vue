<!-- eslint-disable vue/no-unused-components -->
<template>
  <!-- <homeView></homeView> -->
  <weatherComp></weatherComp>
</template>

<script>
import weatherComp from "./components/weather.vue";
// import homeView from "./components/home-view.vue";
export default {
  components: {
    weatherComp,
    // homeView,
  },
};
</script>

<style></style>
