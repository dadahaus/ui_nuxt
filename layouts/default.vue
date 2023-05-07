<template>
  <Nav />

  <div
    class="relative flex min-h-screen flex-col justify-evenly overflow-hidden bg-gray-50 py-6 sm:py-12 p-20"
  >
    <!-- <img
      src="../img/gradient.gif"
      alt=""
      class="absolute top-1/2 left-1/2 max-w-none -translate-x-1/2 -translate-y-1/2"
      width="1308"
      height="180"
      z-index="-100"
    /> -->
    <slot />
    <!-- <AppFooter /> -->
  </div>
</template>
