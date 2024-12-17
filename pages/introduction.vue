<template>
  <div class="md:max-xl:flex max-w-4xl px-10 mx-auto space-y-8 text-center animate-fade-up">
    <div class="flex flex-col items-center">
      <!-- Heading Section -->
      <span class="text-2xl sm:text-3xl md:text-4xl lg:text-5xl font-semibold text-light-gray">
        <span class="type-hello" />, I'm Kryptos
      </span>
      <span class="text-1xl sm:text-3xl md:text-4xl lg:text-0xl font-semibold text-light-gray">
        Owner of kryptosdma.com from the 
        <img src="/icons/world.gif" alt="World icon" class="w-11 h-11 inline-block" />
      </span>

      <!-- Main Introduction Text -->
      <p class="mt-2 text-lg sm:text-xl md:text-2xl lg:text-3xl font-light text-light-gray">
        I try my best to deliver the 
        <span @mouseover="detailshover" class="has-tooltip text-pink-500 border-2 border-pink-500 px-2 py-1 rounded">
          best<span class='tooltip rounded shadow-lg p-1 -mt-8'>
            <img src="/img/details.gif" alt="Details GIF">
          </span>
        </span> products to my customers.
      </p>

      <!-- Additional Content -->
      <p class="mt-4 text-md sm:text-lg md:text-xl lg:text-2xl font-light text-gray-400 leading-relaxed">
        Whether you're looking for top-notch <span class="text-pink-500 font-semibold">DMA hardware</span>, 
        highly optimized <span class="text-pink-500 font-semibold">gaming cheats</span>, or reliable 
        <span class="text-pink-500 font-semibold">firmware solutions</span>, I ensure everything I offer is built with 
        precision and quality in mind.
      </p>
      <p class="mt-2 text-md sm:text-lg md:text-xl lg:text-2xl font-light text-gray-400 leading-relaxed">
        My mission is to stay ahead of the curve, providing the latest and safest tools to help you perform 
        <span class="text-pink-500 font-semibold">faster</span>, play <span class="text-pink-500 font-semibold">smarter</span>, 
        and achieve <span class="text-pink-500 font-semibold">better results</span>.
      </p>

      <!-- Call to Action -->
      <div class="mt-6">
        <a href="https://kryptosdma.com" class="inline-block bg-pink-500 text-white px-6 py-2 rounded hover:bg-pink-600 transition">
          Explore My Products
        </a>
      </div>
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
