<template>
  <div>
    <Header />
    <header>
      <h2>USER SECTION</h2>
    </header>
    <nuxt />
  </div>
</template>
<script>
import Header from "@/components/Header.vue";
export default {
  component: {
    Header
  }
};
</script>
<style>
h2 {
  color: blueviolet;
}
</style>
