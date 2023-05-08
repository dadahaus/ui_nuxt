<template>
  <div>
    <h1
      class="mb-4 text-4xl font-extrabold leading-none tracking-tight text-gray-400 md:text-5xl lg:text-6xl dark:text-gray-700"
    >
      X-height and combination rules
    </h1>
    <p
      class="max-w-screen-sm mb-3 text-lg text-gray-500 md:text-xl dark:text-gray-400"
    >
      In searching for the perfect balance, it was decided to combine two sans
      serif typefaces with similar x height, which is a common principle for
      pairing typefaces
    </p>
  </div>
  <div class="flex flex-col gap-3" style="font-family: Visby">
    <h2>(Heading - h1, h2, h3)</h2>
    <h1
      class="text-5xl md:text-7xl lg:text-9xl font-extrabold leading-none tracking-tight text-gray-400 dark:text-gray-700"
    >
      Visby
    </h1>
    <h2 class="max-w-[31%]">
      <span class="uppercase"
        >a b c d e f g h i j k l m n o p q r s t u v w x y z</span
      >
      a b c d e f g h i j k l m n o p q r s t u v w x y z 0123456789
    </h2>
  </div>
  <div class="flex flex-col gap-3" style="font-family: Interstate">
    <h2>(Heading - h1, h2, h3)</h2>
    <h1
      class="text-2xl md:text-3xl lg:text-5xl leading-none tracking-tight text-gray-400 dark:text-gray-700"
    >
      Interstate
    </h1>
    <h2 class="max-w-[31%]">
      <span class="uppercase"
        >a b c d e f g h i j k l m n o p q r s t u v w x y z</span
      >
      a b c d e f g h i j k l m n o p q r s t u v w x y z 0123456789
    </h2>
  </div>
</template>

<style>
@font-face {
  font-family: Visby;
  src: url(../assets/fonts/visby/VisbyBold.otf);
  font-family: Interstate;
  src: url(../assets/fonts/interstate_sv/Interstate-Regular-Font.ttf);
}
</style>
