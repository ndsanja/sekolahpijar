<template>
  <div class="flex flex-col min-h-screen">
    <Toolbar />
    <main class="flex-1">
      <slot />
    </main>
    <Footer />
    <BottomNavigation />
  </div>
</template>