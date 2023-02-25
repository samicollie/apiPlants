<template>
  <div class="plantitem col-md-6 col-lg-4 col-xl-3 ">
    <figure>
      <img :src="plant.image_url" :alt="plant.common_name" />
    </figure>
    <figcaption>
      <h2>{{ plant.common_name }} <span class="family">({{ plant.family }})</span></h2>
      <p>{{ plant.description }}</p>
    </figcaption>
  </div>
</template>

<script>
export default {
  name: "PlantItem",
  props: {
    plant: Object,
  },
};
</script>

<style></style>
