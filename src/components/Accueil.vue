<template>
  <div class="accueil">
    <p>{{ message }}</p>
  </div>
</template>

<script>
export default {
  name: "Accueil",
  props: {
    message: String
  }
};
</script>

<style>
  .accueil{
    float: right;
  }
</style>
