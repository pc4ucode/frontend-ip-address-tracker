<template>
  <div>
    <BuscarIp />
    <Mapa />
  </div>
</template>

<script>
// import HelloWorld from "../components/HelloWorld";
import BuscarIp from "@/components/BuscaIp/BuscarIp";
import Mapa from "@/components/Mapa/Mapa";

export default {
  name: "Home",
  components: {
    BuscarIp,
    Mapa,
    // HelloWorld,
  },
};
</script>
