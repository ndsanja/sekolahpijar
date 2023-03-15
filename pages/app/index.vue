<script setup>

definePageMeta({
  layout: false,
});
</script>

<template>
  <NuxtLayout name="app">
    <div class="space-y-8 py-8 mx-4">
      <div class="flex gap-4 py-4 overflow-x-scroll w-full">

        <LobiTimelineCard v-for="i in 10" :key="i" />
      </div>

      <LobiFeedCard v-for="i in 20" :key="i" />

    </div>
  </NuxtLayout>
</template>