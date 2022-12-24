<template>
  <div class="home">
    <img alt="Vue logo" src="../assets/logo.png" />
    <HelloWorld msg="Welcome to Your Vue.js App" />
  </div>
</template>

<script>
// @ is an alias to /src
import HelloWorld from "@/components/HelloWorld.vue";

export default {
  name: "HomeView",
  components: {
    HelloWorld,
  },
  created() {
    // alert("olá mundo");
    // console.log("Teste no-console");
  },
};
</script>
<style lang="scss">
.home {
  img {
    display: none;
  }
  background-color: #f00;
}
</style>
