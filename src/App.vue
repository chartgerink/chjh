<template>
  <v-app dark>
    <v-content>
      <HelloWorld />
      <chjh />
      <Content />
    </v-content>
  </v-app>
</template>

<script>
import HelloWorld from "./components/HelloWorld";
import chjh from "./components/chjh";
import Content from "./components/Content";

export default {
  name: "App",
  components: {
    HelloWorld,
    chjh,
    Content
  },
  data() {
    return {
      //
    };
  }
};
</script>
