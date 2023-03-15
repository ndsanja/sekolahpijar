<script setup>

definePageMeta({
  layout: false,
});
</script>

<template>
  <NuxtLayout name="app">
    <div class="space-y-8 py-8 mx-4">

      <LobiFeedCard v-for="i in 20" :key="i" />

    </div>
  </NuxtLayout>
</template>