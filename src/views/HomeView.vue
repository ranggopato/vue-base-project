<template>
  <div class="home">
    <LandingComponent />
  </div>
</template>

<script>
// @ is an alias to /src
import LandingComponent from "@/components/LandingComponent.vue";

export default {
  name: "HomeView",
  components: {
    LandingComponent,
  },
};
</script>
