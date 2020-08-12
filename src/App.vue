<template>
  <Dashboard></Dashboard>
</template>

<script>
import Dashboard from "./components/Dashboard";

export default {
  name: "App",

  components: {
    Dashboard,
  },

  data: () => ({
    //
  }),
};
</script>

<style scoped>
@import url("https://fonts.googleapis.com/css2?family=Roboto:wght@400;500&display=swap");

* {
  margin: 0;
  padding: 0;
  box-sizing: border-box;
  font-family: "Roboto", sans-serif;
}
</style>
