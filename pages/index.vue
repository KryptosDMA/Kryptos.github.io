<template>
  <div class="md:max-xl:flex max-w-4xl px-10 mx-auto space-y-8 text-center animate-fade-up">
    <div class="flex flex-col items-center">
      <span class="text-2xl sm:text-3xl md:text-4xl lg:text-5xl font-semibold text-light-gray"><span
          class="type-hello" />, I'm Kryptos</span>
      <span class="text-1xl sm:text-3xl md:text-4xl lg:text-0xl font-semibold text-light-gray">Owner of kryptosdma.com
        from the <img src="/icons/world.gif" alt="World icon" class="w-11 h-11 inline-block" /></span>
      <p class="mt-2 text-lg sm:text-xl md:text-2xl lg:text-3xl font-light text-light-gray">
        I try my best to deliver the <span @mouseover="detailshover"
          class="has-tooltip text-pink-500 border-2 border-pink-500 px-2 py-1 rounded">best<span
            class='tooltip rounded shadow-lg p-1 -mt-8'><img src="/img/details.gif" alt="Details GIF"></span></span>products to my customers
       
      </p>
    </div>
  </div>
</template>

<script>
export default {
  methods: {
    detailshover() {
      plausible('Details Hover');
    },
    learnhover() {
      plausible('Learn Hover');
    },
  },
};
</script>