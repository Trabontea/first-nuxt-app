<template>
  <section>
    <div
      class="relative flex items-top justify-center min-h-screen bg-gray-100 sm:items-center sm:pt-0"
    >
      <h1>Hello i'm first vue/Nuxt app</h1>
      <!-- <a href="/users">Users</a> -->
      <nuxt-link to="/users">Users</nuxt-link>
    </div>
  </section>
</template>

<script lang="ts">
import Vue from "vue";

export default Vue.extend({
  name: "IndexPage",
});
</script>
