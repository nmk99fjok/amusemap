<template>
  <v-card max-width="500">
    <l-map style="height: 500px" :zoom="zoom" :center="center">
      <l-tile-layer :url="url" :attribution="attribution"></l-tile-layer>
    </l-map>
  </v-card>
</template>

<script>
import { LMap, LTileLayer } from 'vue2-leaflet';

export default {
  components: { LMap, LTileLayer },
  data () {
    return {
      url: 'https://{s}.tile.openstreetmap.org/{z}/{x}/{y}.png',
      attribution:
        '&copy; <a target="_blank" href="http://osm.org/copyright">OpenStreetMap</a> contributors',
      zoom: 8,
      center: [47.313220, -1.319482],
    }
  },
}
</script>
