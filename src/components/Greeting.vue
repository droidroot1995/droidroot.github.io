<template>
  <div class="greeting">
    <h1>{{ msg }}</h1>
    <div class="hello"></div>
  </div>
</template>

<script>
export default {
  name: "Greeting",
  props: {
    msg: String
  }
};
</script>

<style scoped></style>
