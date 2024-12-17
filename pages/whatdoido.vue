<template>
    <div class="md:max-xl:flex max-w-4xl px-10 mx-auto space-y-8 text-center animate-fade-up">
      <div class="flex flex-col items-center">
        <!-- Heading Section -->
        <span class="text-2xl sm:text-3xl md:text-4xl lg:text-5xl font-semibold text-light-gray">
          <span class="type-hello" /> What I Offer
        </span>
        <span class="text-1xl sm:text-3xl md:text-4xl lg:text-0xl font-semibold text-light-gray">
          Premium solutions crafted for the <class="w-11 h-11 inline-block/>
        </span>
  
        <!-- Main Content -->
        <p class="mt-2 text-lg sm:text-xl md:text-2xl lg:text-3xl font-light text-light-gray">
          We at Kryptos DMA specialize in delivering high-performance <span class="text-pink-500 font-semibold">DMA products</span> and 
          tools for cheese enthusiasts.
        </p>
  
        <!-- Feature List -->
        <div class="mt-6 grid grid-cols-1 sm:grid-cols-2 gap-6">
          <!-- DMA Hardware -->
          <div class="flex flex-col items-center space-y-4">
            <class="w-16 h-16 />
            <h3 class="text-lg font-semibold text-pink-500">DMA Hardware</h3>
            <p class="text-md text-gray-400">
              Reliable and emulated <span class="text-pink-500 font-semibold">firmware</span> solutions for DMA cards.
            </p>
          </div>
  
          <!-- Gaming Cheats -->
          <div class="flex flex-col items-center space-y-4">
            <class="w-16 h-16 />
            <h3 class="text-lg font-semibold text-pink-500">Gaming Cheats</h3>
            <p class="text-md text-gray-400">
              Optimized cheats for <span class="text-pink-500 font-semibold">Valorant</span>, <span class="text-pink-500 font-semibold">Fortnite</span>, 
              and other top games.
            </p>
          </div>
  
          <!-- Ultimate Bundles -->
          <div class="flex flex-col items-center space-y-4">
            <class="w-16 h-16/>
            <h3 class="text-lg font-semibold text-pink-500">Ultimate Bundles</h3>
            <p class="text-md text-gray-400">
              Get the best value with my premium <span class="text-pink-500 font-semibold">Ultimate Bundles</span>.
            </p>
          </div>
  
          <!-- Custom Solutions -->
          <div class="flex flex-col items-center space-y-4">
            <class="w-16 h-16/>
            <h3 class="text-lg font-semibold text-pink-500">Custom Solutions</h3>
            <p class="text-md text-gray-400">
              Tailored tools to meet your specific <span class="text-pink-500 font-semibold">gaming</span> or tech needs.
            </p>
          </div>
        </div>
  
        <!-- Call to Action -->
        <div class="mt-8">
          <a href="https://kryptosdma.com" class="inline-block bg-pink-500 text-white px-6 py-2 rounded hover:bg-pink-600 transition">
            Browse Our Products
          </a>
        </div>
      </div>
    </div>
  </template>
  
  <script>
  export default {
    methods: {
      plausibleEvent(event) {
        plausible(event);
      },
    },
  };
  </script>
  