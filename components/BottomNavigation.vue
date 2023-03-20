<script>
export default {
  data: () => ({ value: 1 }),
}
</script>

<template>
  <v-bottom-navigation v-model="value" color="teal" grow class="lg:!hidden" style="height: 50px;">
    <v-btn>
      <v-icon style="font-size: x-large;">mdi-home-outline</v-icon>

      <span style="font-size: xx-small;">Lobi</span>
    </v-btn>

    <v-btn>
      <v-icon style="font-size: x-large;">mdi-book-open-page-variant-outline</v-icon>

      <span style="font-size: xx-small;">E-Learning</span>

    </v-btn>

    <v-btn>
      <v-icon style="font-size: x-large;">mdi-monitor-edit</v-icon>

      <span style="font-size: xx-small;">Studio</span>

    </v-btn>

    <v-btn>
      <v-icon style="font-size: x-large;">mdi-calendar-clock-outline</v-icon>

      <span style="font-size: xx-small;">Agenda</span>

    </v-btn>

    <v-btn>
      <v-icon style="font-size: x-large;">mdi-account-outline</v-icon>

      <span style="font-size: xx-small;">Profile</span>

    </v-btn>
  </v-bottom-navigation>
</template>