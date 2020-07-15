<template>
  <div id="app">
    <Navbar />
    <b-container>
      <router-view />
    </b-container>
  </div>
</template>


<script>
import Navbar from "@/components/Navbar";

export default {
  components: {
    Navbar
  }
};
</script>

<style lang="scss">
body {
  font-family: "Roboto", "Segoe UI", Tahoma, Geneva, Verdana, sans-serif !important;
}
</style>
