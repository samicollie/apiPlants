<template>
  <div id="app">
    <the-header></the-header>
    <PlantList />
    <the-footer></the-footer>
  </div>
</template>

<script>
import TheHeader from "./components/TheHeader.vue";
import PlantList from "./components/Plant/PlantList.vue";
import TheFooter from "./components/TheFooter.vue";

export default {
  name: "App",
  components: {
    TheHeader,
    PlantList,
    TheFooter,
  },
};
</script>

<style></style>
