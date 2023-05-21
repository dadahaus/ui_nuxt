<template>
  <div class="container">
    <div
      class="smallcopy text-sm md:text-lg lg:text-5xl md:w-[70%] lg:w-[50%] text-gray-500 dark:text-gray-400"
    >
      <slot />
    </div>
  </div>
</template>

<style>
.container {
  position: relative;
}
.smallcopy::before {
  content: "";
  position: absolute;
  background-color: beige;
  width: 30%;
  height: 3px;
  top: -15%;
}
</style>
