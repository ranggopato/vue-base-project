<template>
  <div class="landing">
    <div>
      <h1>Welcome To My Vue Project</h1>
    </div>
  </div>
</template>

<script>
export default {
  name: "LandingComponent",
  props: {},
};
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
.landing {
  display: flex;
  justify-content: center;
  align-items: center;
  min-height: 90vh;
}
</style>
