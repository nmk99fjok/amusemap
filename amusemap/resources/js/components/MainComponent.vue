<template>
  <v-app>
    <v-app-bar app color="blue" dark>
      <v-toolbar-title>TEST</v-toolbar-title>
    </v-app-bar>
    <v-main>
      <v-container>
        <v-row align="center">
          <v-col cols="6">
            <store-panel></store-panel>
          </v-col>

          <v-col cols="6">
            <map-panel></map-panel>
          </v-col>
        </v-row>
      </v-container>
    </v-main>
  </v-app>
</template>

<script>
import MapPanel from './MapPanel.vue'

export default {
  components: {
    MapPanel
  },
}
</script>
