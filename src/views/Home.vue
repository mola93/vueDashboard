<template>
  <div class="home">
    <Header />
    <img alt="Vue logo" src="../assets/logo.png" />
    <HelloWorld msg="Welcome man  " />
  </div>
</template>

<script>
// @ is an alias to /src
import HelloWorld from "@/components/HelloWorld.vue";
import Header from "@/components/Header.vue";

export default {
  name: "home",
  components: {
    HelloWorld,
    Header
  }
};
</script>
