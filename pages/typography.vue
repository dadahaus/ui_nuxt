<template>
  <div
    class="flex flex-col md:basis-[45%] lg:basis-[45%] justify-start h-auto gap-8"
  >
    <Icon>
      <img
        src="../img/typography.svg"
        alt=""
        srcset=""
        style="object-fit: cover"
      />
    </Icon>
    <LargeCopy title="large copy"> Typography</LargeCopy>

    <SmallCopy class="mt-[1ch] md:mt-[4ch]">
      (Rules of) Type combination
    </SmallCopy>

    <Copy>
      In searching for the perfect balance, it was decided to combine two sans
      serif typefaces with similar x height, which is a common principle for
      pairing typefaces.
    </Copy>
  </div>
  <div>
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
