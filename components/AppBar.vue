<template>
  <v-app-bar class="sticky top-0 elevation-0">
    <template v-slot:prepend>
      <v-app-bar-nav-icon></v-app-bar-nav-icon>
    </template>

    <v-app-bar-title>Pijar</v-app-bar-title>

    <v-spacer></v-spacer>

    <v-btn icon>
      <v-icon>mdi-theme-light-dark</v-icon>
    </v-btn>

    <v-btn icon>
      <v-icon>mdi-bell-outline</v-icon>
    </v-btn>

    <v-btn icon>
      <v-icon>mdi-chat-outline</v-icon>
    </v-btn>
  </v-app-bar>
</template>