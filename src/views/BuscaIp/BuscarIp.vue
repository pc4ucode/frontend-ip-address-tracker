<template>
  <v-row>
    <v-col cols="12">
      <v-img src="@/assets/pattern-bg.png">
        <v-row>
          <v-col cols="12">
            <p class="text-h5 font-weight-black white--text text-center">
              Ip Address Tracker
            </p>
          </v-col>
          <v-col cols="12">
            <div class="d-flex">
              <v-text-field
                solo
                label="Append outer"
                append-outer-icon="mdi-map-marker"
              ></v-text-field>
            </div>
          </v-col>
        </v-row>
      </v-img>
    </v-col>
  </v-row>
</template>

<script>
export default {
  name: "BuscarIp",
};
</script>

<style scoped></style>
