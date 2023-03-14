<template>
  <div class="flex flex-col min-h-screen">
    <AppBar />
    <main class="flex-1 mt-16 mb-12">
      <slot />
    </main>
    <Footer />
    <BottomNavigation />
  </div>
</template>