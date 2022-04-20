<template>
  <section>
    <Hero />
    <div
      class="relative flex items-top justify-center min-h-screen bg-gray-100 sm:items-center sm:pt-0"
    >
      <h1>Hello i'm first vue/Nuxt app</h1>
      <!-- <a href="/users">Users</a> -->
      <nuxt-link to="/users">Users</nuxt-link>
      <nuxt-link to="/products">Products</nuxt-link>
    </div>
  </section>
</template>

<script lang="ts">
import Vue from "vue";
import Hero from "~/components/Hero.vue";

export default Vue.extend({
  components: {
    Hero,
  },
  name: "IndexPage",
  layout: "default",
});
</script>
<style scoped>

</style>
