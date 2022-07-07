<template>
  <v-app>
    <v-app-bar app color="blue" dark>
      <v-toolbar-title>TEST</v-toolbar-title>
    </v-app-bar>
    <v-main>
      <v-container>
        <map-panel></map-panel>
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
