<template>
  <div>
    <section class="swiper">SWIPER</section>

   <section class="choose bg-gray-50 py-20">
  <div class="container mx-auto px-4 text-center">
 
    <h2
      class="text-2xl md:text-3xl font-bold text-gray-900 mb-2 opacity-0 translate-y-4 animate-fade-up"
    >
      Why Choose Us
    </h2>
    <p
      class="text-gray-500 mb-12 max-w-2xl mx-auto opacity-0 translate-y-4 animate-fade-up [animation-delay:0.15s]"
    >
      Nulla quis curabitur velit volutpat auctor bibendum consectetur sit.
    </p>

  
    <div
      class="grid grid-cols-1 md:grid-cols-4 gap-10 opacity-0 translate-y-4 animate-fade-up [animation-delay:0.3s]"
    >

      <div
        class="flex flex-col items-center text-center p-6 rounded-2xl bg-white shadow-sm hover:shadow-lg transition-all duration-300 hover:-translate-y-2"
      >
        <div
          class="p-4 rounded-full bg-blue-50 text-blue-600 mb-4 transition-all duration-300 group-hover:bg-blue-100"
        >
          <svg
            class="w-10 h-10 transition-transform duration-300 group-hover:scale-110"
            xmlns="http://www.w3.org/2000/svg"
            viewBox="0 0 24 24"
            fill="none"
            stroke="currentColor"
            stroke-width="2"
            stroke-linecap="round"
            stroke-linejoin="round"
          >
            <path
              d="M5 17H4a2 2 0 0 1-2-2V5a2 2 0 0 1 2-2h16a2 2 0 0 1 2 2v10a2 2 0 0 1-2 2h-1"
            />
            <path d="m12 16l6 5H6z" />
          </svg>
        </div>
        <h3 class="font-semibold text-gray-800 mb-3">Trusted By Thousands</h3>
        <p class="text-gray-500 text-sm leading-relaxed max-w-[240px]">
          With over 1 million+ homes for sale available on the website, Trulia
          can match you with a house you will want to call home.
        </p>
      </div>


      <div
        class="flex flex-col items-center text-center p-6 rounded-2xl bg-white shadow-sm hover:shadow-lg transition-all duration-300 hover:-translate-y-2"
      >
        <div
          class="p-4 rounded-full bg-blue-50 text-blue-600 mb-4 transition-all duration-300 group-hover:bg-blue-100"
        >
          <svg
            class="w-10 h-10 transition-transform duration-300 group-hover:scale-110"
            xmlns="http://www.w3.org/2000/svg"
            viewBox="0 0 24 24"
            fill="none"
            stroke="currentColor"
            stroke-width="2"
            stroke-linecap="round"
            stroke-linejoin="round"
          >
            <rect width="16" height="20" x="4" y="2" rx="2" />
            <path d="M11 18h2" />
          </svg>
        </div>
        <h3 class="font-semibold text-gray-800 mb-3">
          Wide Range Of Properties
        </h3>
        <p class="text-gray-500 text-sm leading-relaxed max-w-[240px]">
          With over 1 million+ homes for sale available on the website, Trulia
          can match you with a house you will want to call home.
        </p>
      </div>

    
      <div
        class="flex flex-col items-center text-center p-6 rounded-2xl bg-white shadow-sm hover:shadow-lg transition-all duration-300 hover:-translate-y-2"
      >
        <div
          class="p-4 rounded-full bg-blue-50 text-blue-600 mb-4 transition-all duration-300 group-hover:bg-blue-100"
        >
          <svg
            class="w-10 h-10 transition-transform duration-300 group-hover:scale-110"
            xmlns="http://www.w3.org/2000/svg"
            viewBox="0 0 24 24"
            fill="none"
            stroke="currentColor"
            stroke-width="2"
            stroke-linecap="round"
            stroke-linejoin="round"
          >
            <path
              stroke-linejoin="round"
              d="M15.5 4H18a2 2 0 0 1 2 2v13a2 2 0 0 1-2 2H6a2 2 0 0 1-2-2V6a2 2 0 0 1 2-2h2.5"
            />
            <path
              stroke-linejoin="round"
              d="M8.621 3.515A2 2 0 0 1 10.561 2h2.877a2 2 0 0 1 1.94 1.515L16 6H8z"
            />
            <path d="M9 12h6m-6 4h6" />
          </svg>
        </div>
        <h3 class="font-semibold text-gray-800 mb-3">Financing Made Easy</h3>
        <p class="text-gray-500 text-sm leading-relaxed max-w-[240px]">
          With over 1 million+ homes for sale available on the website, Trulia
          can match you with a house you will want to call home.
        </p>
      </div>

      <!-- Item 4 -->
      <div
        class="flex flex-col items-center text-center p-6 rounded-2xl bg-white shadow-sm hover:shadow-lg transition-all duration-300 hover:-translate-y-2"
      >
        <div
          class="p-4 rounded-full bg-blue-50 text-blue-600 mb-4 transition-all duration-300 group-hover:bg-blue-100"
        >
          <svg
            class="w-10 h-10 transition-transform duration-300 group-hover:scale-110"
            xmlns="http://www.w3.org/2000/svg"
            viewBox="0 0 24 24"
            fill="none"
            stroke="currentColor"
            stroke-width="2"
            stroke-linecap="round"
            stroke-linejoin="round"
          >
            <circle cx="12" cy="12" r="10" />
            <ellipse
              cx="12"
              cy="12"
              rx="10"
              ry="4"
              transform="rotate(90 12 12)"
            />
            <path d="M2 12h20" />
          </svg>
        </div>
        <h3 class="font-semibold text-gray-800 mb-3">See Neighborhoods</h3>
        <p class="text-gray-500 text-sm leading-relaxed max-w-[240px]">
          With over 1 million+ homes for sale available on the website, Trulia
          can match you with a house you will want to call home.
        </p>
      </div>
    </div>
  </div>
</section>
  </div>
</template>

<script setup>
</script>

<style  scoped>
  @keyframes fade-up {
    0% {
      opacity: 0;
      transform: translateY(20px);
    }
    100% {
      opacity: 1;
      transform: translateY(0);
    }
  }

  .animate-fade-up {
    animation: fade-up 0.8s ease-out forwards;
  }
</style>