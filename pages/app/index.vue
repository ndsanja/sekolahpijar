<script setup>

definePageMeta({
  layout: false,
});
</script>

<template>
  <NuxtLayout name="app">
    <Breadcrumbs class="sticky top-[45px] z-40 bg-white" />
    <div class="mt-[50px] md:!mt-0 flex flex-col md:flex-row mx-4 gap-4">
      <div
        class="hidden lg:flex min-w-[250px] overflow-x-scroll lg:min-h-[calc(100vh-45px)] lg:max-h-[calc(100vh-45px)] lg:overflow-y-auto lg:sticky lg:top-[80px] ">
        <MainMenuList />
      </div>
      <div
        class="flex md:sticky md:top-[80px] md:flex-col md:order-2 md:w-[300px] gap-4 overflow-x-scroll w-full md:min-h-[calc(100vh-45px)] md:max-h-[calc(100vh-45px)] md:overflow-y-auto">
        <LobiTimelineCard v-for="i in 10" :key="i" />
      </div>
      <div class="md:flex-1 space-y-8 md:mt-[45px]">
        <LobiFeedCard v-for="i in 20" :key="i" />
      </div>
    </div>
  </NuxtLayout>
</template>