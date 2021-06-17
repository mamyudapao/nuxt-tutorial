<template>
  <div>
    <Header />
    <Nuxt />
  </div>
</template>
<script>
import Header from "@/components/Header";
export default {
  components: {
    Header
  }
};
</script>
<style>
html,
body {
  margin: 0;
  padding: 0;
}
</style>
