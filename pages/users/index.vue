<template>
  <div class="container">
    <Hero />
    <h1>This is the users page</h1>
    <input type="text" v-model="userId" />
    <button @click="onLoadUser">Load User</button>
  </div>
</template>

<script>
import Hero from "~/components/Hero.vue";
export default {
  components: {
    Hero,
  },
  data() {
    return {
      userId: "",
    };
  },
  methods: {
    onLoadUser() {
      this.$router.push("/users/" + this.userId);
    },
  },
  layout: "users",
};
</script>
