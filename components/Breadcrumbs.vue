<script setup>

const items = ref([
  {
    title: 'Lobi',
    disabled: false,
    href: 'breadcrumbs_dashboard',
  },
  {
    title: 'Organisasi',
    disabled: false,
    href: 'breadcrumbs_link_1',
  },
  {
    title: 'SMA Negeri 1 Srengat',
    disabled: true,
    href: 'breadcrumbs_link_2',
  },
])

</script>

<template>
  <v-breadcrumbs :items="items" class="!h-[20px] !text-xs">
    <template v-slot:prepend>
      <v-icon size="medium" icon="mdi-vuetify"></v-icon>
    </template>
  </v-breadcrumbs>
</template>