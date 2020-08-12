<template>
  <div class="dashboard">
    <Navigation></Navigation>
    <Content></Content>
  </div>
</template>

<script>
import Navigation from "./Navigation";
import Content from "./Content";
export default {
  components: {
    Navigation,
    Content,
  },
};
</script>

<style scoped>
.dashboard {
  display: flex;
  width: 100%;
  height: 100vh;
}
</style>