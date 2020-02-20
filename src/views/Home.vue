<template>
  <div class="home">
    <img alt="Vue logo" src="../assets/logo.png" />
    <HelloWorld msg="Welcome to Your Vue.js App" />

    <h1>WhiteBoard Area</h1>
    <h2>Key Terms</h2>

    <h3>Mongoose</h3>
    <p>
      mongodb object modeling for node.js or JS Library that allows you the
      ability to define schemas with strongly typed data or High Level API's for
      interaction w/MongoDB, using JS
    </p>
    <br />

    <h3>Dapper</h3>
    <p>Object mapper for .NET - Maps between Database and Language</p>

    <h2></h2>
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
