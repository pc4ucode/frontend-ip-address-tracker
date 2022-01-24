<template>
  <v-container fluid>
    <BuscarIp />
    <hello-world v-if="false" />
  </v-container>
</template>

<script>
import HelloWorld from "../components/HelloWorld";
import BuscarIp from "@/views/BuscaIp/BuscarIp";

export default {
  name: "Home",

  components: {
    BuscarIp,
    HelloWorld,
  },
};
</script>
