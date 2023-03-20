<script setup>

definePageMeta({
  layout: false,
});
</script>

<template>
  <NuxtLayout name="app">
    <div class="flex flex-col md:flex-row mx-4 gap-4">
      <div
        class="hidden lg:flex min-w-[250px] overflow-x-scroll lg:min-h-[calc(100vh-65px)] lg:max-h-[calc(100vh-65px)] lg:overflow-y-auto lg:sticky lg:top-[65px] ">
        <MainMenuList />
      </div>
      <div
        class="flex md:sticky md:top-[65px] md:flex-col md:order-2 md:w-[300px] gap-4 overflow-x-scroll w-full md:min-h-[calc(100vh-65px)] md:max-h-[calc(100vh-65px)] md:overflow-y-auto">
        <LobiTimelineCard v-for="i in 10" :key="i" />
      </div>
      <div class="md:flex-1 space-y-8">
        <LobiFeedCard v-for="i in 20" :key="i" />
      </div>
    </div>
  </NuxtLayout>
</template>