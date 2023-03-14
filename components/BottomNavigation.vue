<script>
export default {
  data: () => ({ value: 1 }),
}
</script>

<template>
  <v-bottom-navigation v-model="value" color="teal" grow class="d-md-none">
    <v-btn>
      <v-icon>mdi-history</v-icon>

      Lobi
    </v-btn>

    <v-btn>
      <v-icon>mdi-heart</v-icon>

      Explores
    </v-btn>

    <v-btn>
      <v-icon>mdi-map-marker</v-icon>

      Studio
    </v-btn>

    <v-btn>
      <v-icon>mdi-map-marker</v-icon>

      Agenda
    </v-btn>

    <v-btn>
      <v-icon>mdi-map-marker</v-icon>

      Profile
    </v-btn>
  </v-bottom-navigation>
</template>