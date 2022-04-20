<template>
  <h1>A single user, with ID {{ $route.params.id }}</h1>
</template>

<script>
export default {
  validate(data) {
    console.log("data::", data);
    // aici se poate folosi pentru validare
    // return data.params.id == 1;
    // verifing if the id is a number, if not returns error
    return /^\d+$/.test(data.params.id);
  },
  layout: 'users'
};
</script>
