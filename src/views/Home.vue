<template>
  <div class="home">
    <Greeting msg="Welcome to my portfolio page!" />
  </div>
</template>

<script>
// @ is an alias to /src
import Greeting from "@/components/Greeting.vue";

export default {
  name: "home",
  components: {
    Greeting
  }
};
</script>
