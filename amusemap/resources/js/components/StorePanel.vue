<template>
  <v-card max-width="350" class="mx-auto">
    <!-- 画像 -->
    <v-card-title>店舗名</v-card-title>
    <v-card-text>
      <v-row
        align="center"
        class="mx-0"
      >
        <v-rating
          :value="4.0"
          color="amber"
          dense
          half-increments
          readonly
          size="14"
        ></v-rating>

        <div class="grey--text ms-4">
          4.0 (25)
        </div>
      </v-row>
    </v-card-text>

    <v-divider class="mx-4"></v-divider>

    <v-list>
      <v-list-item>
        <v-list-item-icon class="mx-auto">
          <v-icon>mdi-map-marker-outline</v-icon>
        </v-list-item-icon>

        <v-list-item-content>
          <v-list-item-subtitle>住所</v-list-item-subtitle>
        </v-list-item-content>
      </v-list-item>

      <v-list-item>
        <v-list-item-icon class="mx-auto">
          <v-icon>mdi-clock-outline</v-icon>
        </v-list-item-icon>

        <v-list-item-content>
          <v-list-item-subtitle>営業時間</v-list-item-subtitle>
        </v-list-item-content>
      </v-list-item>

      <v-list-item>
        <v-list-item-icon class="mx-auto">
          <v-icon>mdi-web</v-icon>
        </v-list-item-icon>

        <v-list-item-content>
          <v-list-item-subtitle>ウェブサイト</v-list-item-subtitle>
        </v-list-item-content>
      </v-list-item>
    </v-list>

    <v-divider class="mx-4"></v-divider>

    <v-card-title>コメント</v-card-title>
  </v-card>
</template>

<script>
  export default {
    data () {
      return {

      }
    }
  }
</script>
