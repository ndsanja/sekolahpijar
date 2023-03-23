<script>
export default {
  data() {
    return {
      model: 'tab-2',
      text: 'Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat.',
    }
  },
}
</script>

<template>
  <v-tabs v-model="model" grow class="!sticky !top-0">
    <v-tab v-for="i in 3" :key="i" :value="i">
      Item {{ i }}
    </v-tab>
  </v-tabs>
</template>