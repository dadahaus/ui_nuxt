<template>
  <div class="pl-10 pr-20 flex flex-col justify-evenly h-auto gap-8">
    <LargeCopy title="large copy"> Navigation </LargeCopy>

    <SmallCopy> Playful+Classic </SmallCopy>

    <Copy>
      The border radius was set to a maximum of 50% as to convey the playfulness
      of the brand. However, for the contact form fields that was significantly
      reduced
    </Copy>
  </div>
  <div class="text-gray-400 flex flex-col gap-3" style="font-family: Visby">
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
  <div
    class="text-gray-400 flex flex-col gap-3"
    style="font-family: Interstate"
  >
    <h2>(Heading - h1, h2, h3)</h2>
    <h1
      class="text-2xl md:text-3xl lg:text-5xl leading-none tracking-tight dark:text-gray-700"
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
  font-family: Regattia;
  src: url(../assets/fonts/regattia-bold-webfont.woff);
}
</style>
