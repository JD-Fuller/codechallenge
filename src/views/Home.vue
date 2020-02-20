<template>
  <div class="home">
    <img alt="Vue logo" src="../assets/logo.png" />
    <HelloWorld msg="Welcome to Your Vue.js App" />

    <h1>WhiteBoard Area</h1>

    <h1>Mongoose</h1>
    <p>
      mongodb object modeling for node.js or JS Library that allows you the
      ability to define schemas with strongly typed data or High Level API's for
      interaction w/MongoDB, using JS
    </p>
    <br />

    <h2>Dapper</h2>
    <p></p>
  </div>
</template>

<script>
// @ is an alias to /src
import HelloWorld from "@/components/HelloWorld.vue";

export default {
  name: "Home",
  components: {
    HelloWorld
  }
};
</script>
