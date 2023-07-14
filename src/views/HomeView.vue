<template>
  <div class="home">
    <img class="logo" alt="Vue logo" src="../assets/vs.png" />
    <HelloWorld msg="Welcome to Your Vue.js Skeleton app" />
  </div>
</template>
<style scoped>
img {
  width: 200px;
}
</style>

<script>
// @ is an alias to /src
import HelloWorld from "@/components/HelloWorld.vue";

export default {
  name: "HomeView",
  components: {
    HelloWorld,
  },
};
</script>
