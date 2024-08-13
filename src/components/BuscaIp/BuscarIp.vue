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
                append-icon="mdi-arrow-right-bold-box"
                style="max-width: 25%"
                v-model="searchInput"
                @click:append="searchIpAddress()"
              >
              </v-text-field>
            </div>
          </v-col>
          <v-col cols="12">
            <v-card class="mx-auto mb-4" max-width="980" outlined>
              <v-row class="py-7 px-5">
                <v-col cols="3">
                  <div class="text-overline mb-4">IP ADDRESS</div>
                  <v-list-item-title class="text-h5 mb-1">
                    192.212.174.101
                  </v-list-item-title>
                </v-col>
                <v-divider vertical />
                <v-col cols="3">
                  <div class="text-overline mb-4">LOCATION</div>
                  <v-list-item-title class="text-h5 mb-1">
                    Brooklyn, NY 10001
                  </v-list-item-title>
                </v-col>
                <v-divider vertical />
                <v-col cols="3">
                  <div class="text-overline mb-4">TIMEZONE</div>
                  <v-list-item-title class="text-h5 mb-1">
                    UTC-05:00
                  </v-list-item-title>
                </v-col>
                <v-divider vertical />
                <v-col cols="3">
                  <div class="text-overline mb-4">ISP</div>
                  <v-list-item-title class="text-h5 mb-1">
                    SpaceX Starlink
                  </v-list-item-title>
                </v-col>
              </v-row>
            </v-card>
          </v-col>
        </v-row>
      </v-img>
    </v-col>
  </v-row>
</template>

<script>
export default {
  name: "BuscarIp",
  data: () => ({
    searchInput: "",
  }),
  methods: {
    searchIpAddress() {
      console.log("teste function", this.searchInput);
    },
  },
};
</script>

<style scoped></style>
