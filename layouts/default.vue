<template>
  <Nav />
  <div class="dark:bg-gray-800 dark:text-gray-200">
    <p class="p-4 pb-2">
      <select
        v-model="$colorMode.preference"
        class="border w-24 h-8 dark:bg-gray-900 dark:text-white dark:border-gray-700"
      >
        <option value="system">System</option>
        <option value="light">Light</option>
        <option value="dark">Dark</option>
      </select>
    </p>
    <nuxt class="mx-auto p-4" />
  </div>
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
