<template>
  <v-row>
    <v-col cols="12">
      <v-img src="@/assets/pattern-bg.png">
        <v-row>
          <v-col cols="12">
            <p class="text-h5 font-weight-black white--text text-center mt-8">
              Ip Address Tracker
            </p>
          </v-col>
          <v-col cols="12">
            <div class="d-flex justify-center">
              <v-text-field
                solo
                label="Search for any IP address or domain"
                append-outer-icon="mdi-map-marker"
                style="max-width: 50%"
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
