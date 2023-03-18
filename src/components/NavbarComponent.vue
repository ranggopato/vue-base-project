<template>
  <nav class="navbar">
    <div>
      <img class="logo" src="../assets/logo.png" alt="logo" />
    </div>
    <div>
      <router-link to="/">Home</router-link>
      <router-link to="/about">About</router-link>
    </div>
  </nav>
</template>
<script>
export default {
  name: "NavbarComponent",
  props: {},
};
</script>
<style scoped>
nav {
  margin: 0%;
}
.navbar {
  display: flex;
  justify-content: space-between;
  min-height: 10vh;
  background-color: #aaa6a4;
  align-items: center;
}
.logo {
  width: 50px;
  height: 50px;
  margin-left: 20px;
}
</style>
