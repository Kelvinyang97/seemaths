<template>
  <div class="home">
    <img alt="Vue logo" src="../assets/logo.png" />
    <HelloWorld msg="Welcome to Your Vue.js App" />
    <GraphArea/>
  </div>
</template>

<script>
// @ is an alias to /src
import HelloWorld from "@/components/HelloWorld.vue";
import GraphArea from "@/components/GraphArea.vue";

export default {
  name: "Home",
  components: {
    HelloWorld,
    GraphArea
  }
};
</script>
