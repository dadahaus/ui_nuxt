<template>
  <div class="flex flex-col basis-1/3 gap-8">
    <div
      style="background-color: var(--color-primary)"
      class="w-16 h-16 rounded-md"
    ></div>
    <div
      style="background-color: var(--color-secondary)"
      class="w-16 h-16 rounded-md"
    ></div>
    <div
      style="background-color: var(--color-secondary-one)"
      class="w-16 h-16 rounded-md"
    ></div>
    <div
      style="background-color: var(--color-secondary-two)"
      class="w-16 h-16 rounded-md"
    ></div>
    <div class="w-16 h-16 bg--700 rounded-md"></div>
  </div>

  <span>
    <slot />
  </span>
</template>
