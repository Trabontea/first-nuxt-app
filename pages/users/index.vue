<template>
  <div class="container">
    <h1>This is the users page</h1>
    <input type="text" v-model="userId" />
    <button @click="onLoadUser">Load User</button>
  </div>
</template>

<script>
export default {
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
};
</script>
