<template>
  <header class="header">
    <ul class="nav-items">
      <li>
        <nuxt-link to="/">Home</nuxt-link>
      </li>
      <li>
        <nuxt-link to="/users">Users</nuxt-link>
      </li>

      <li>
        <nuxt-link to="/">Products</nuxt-link>
      </li>
    </ul>
  </header>
</template>
<style scoped>
.header {
  width: 100%;
  height: 60px;
  display: flex;
  justify-content: center;
  align-items: center;

  background-color: darkslategrey;
}

.nav-items {
  padding: 0;
  list-style: none;
  margin: 0;
  display: flex;
  justify-content: space-around;
  align-items: center;
  width: 80%;
}

a {
  color: orange;
}

a:hover {
  color: red;
}
</style>
