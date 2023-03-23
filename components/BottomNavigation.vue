<script>
export default {
  data: () => ({ value: 1 }),
}
</script>

<template>
  <v-bottom-navigation v-model="value" color="teal" grow class="md:!hidden !h-[50px]">
    <v-btn>
      <v-icon class="!text-2xl">mdi-home-outline</v-icon>

      <span class="!text-[9px]">Lobi</span>
    </v-btn>

    <v-btn>
      <v-icon class="!text-2xl">mdi-book-open-page-variant-outline</v-icon>

      <span class="!text-[9px]">E-Learning</span>

    </v-btn>

    <v-btn>
      <v-icon class="!text-2xl">mdi-monitor-edit</v-icon>

      <span class="!text-[9px]">Studio</span>

    </v-btn>

    <v-btn>
      <v-icon class="!text-2xl">mdi-calendar-clock-outline</v-icon>

      <span class="!text-[9px]">Agenda</span>

    </v-btn>

    <v-btn>
      <v-icon class="!text-2xl">mdi-account-outline</v-icon>

      <span class="!text-[9px]">Profile</span>

    </v-btn>
  </v-bottom-navigation>
</template>