<template>
  <div class="home">
    <HelloWorld msg="Welcome to Your Vue.js App" />
    <Accueil message="Je fais des tests et ça m'amuse"/>
  </div>
</template>

<script>
// @ is an alias to /src
import HelloWorld from "@/components/HelloWorld.vue";
import Accueil from "@/components/Accueil.vue";

export default {
  name: "Home",
  components: {
    HelloWorld,
    Accueil
  }
};
</script>
