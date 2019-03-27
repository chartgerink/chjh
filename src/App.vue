<template>
  <v-app dark>
    <v-content>
      <!-- <HelloWorld /> -->
      <!-- <chjh /> -->
      <Header />
      <!-- <Funding /> -->
      <!-- <Timeline /> -->
    </v-content>
  </v-app>
</template>

<script>
// import HelloWorld from "./components/HelloWorld";
// import chjh from "./components/chjh";
import Header from "./components/Header";
// import Funding from "./components/Funding";
// import Timeline from "./components/Timeline";

export default {
  name: "App",
  components: {
    // HelloWorld,
    //   chjh,
    Header
    // Funding,
    // Timeline
  },
  data() {
    return {
      //
    };
  }
};
</script>
