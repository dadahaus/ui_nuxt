<template>
  <Nav />
  <div class="pl-10 p-4">
    <h1>Color mode: {{ $colorMode.value }}</h1>
    <select v-model="$colorMode.preference">
      <option value="system">System</option>
      <option value="light">Light</option>
      <option value="dark">Dark</option>
      <option value="sepia">Sepia</option>
    </select>
  </div>

  <div class="pl-10 pr-10 flex flex-wrap justify-evenly h-auto gap-8">
    <slot />
  </div>

  <!-- <img
      src="../img/gradient.gif"
      alt=""
      class="absolute top-1/2 left-1/2 max-w-none -translate-x-1/2 -translate-y-1/2"
      width="1308"
      height="180"
      z-index="-100"
    /> -->
  <!-- <AppFooter /> -->
</template>

<style>
@import url("assets/css/index.css");
@import url("assets/css/globals.css");
</style>
