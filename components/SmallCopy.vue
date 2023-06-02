<template>
  <div class="container">
    <div
      class="smallcopy text-xl md:text-3xl lg:text-5xl md:w-[70%] text-violet-500 dark:text-violet-400"
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
  background-color: gray;
  width: 7ch;
  height: 0.08ch;
  top: -15%;
}
</style>
