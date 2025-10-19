<template>
  <div
    class="w-[380px] h-[429px] rounded-2xl overflow-hidden shadow-lg border border-gray-200 bg-white hover:shadow-xl transition-shadow duration-300"
  >
    <div class="relative">
      <img
        src="../assets/images/statik.png"
        alt="Apartment"
        class="w-full h-52 object-cover"
      />
      <div class="absolute top-3 left-3 flex   gap-48">
        <span
          class="bg-blue-600 text-white text-xs font-semibold px-3 py-1 rounded-md"
          >FEATURED</span
        >
        <span
          class="bg-slate-800 text-white text-xs font-semibold px-3 py-1 rounded-md"
          >FOR SALE</span
        >
      </div>  
      <div class="absolute -bottom-5 right-5">
        <img
          src="../assets/images/tag-photo.svg"
          alt="Owner"
          class="w-10 h-10 rounded-full border-2 border-white shadow-md"
        />
      </div>
    </div>

    <div class="px-5 pt-7 pb-5">
      <h2 class="text-lg font-semibold text-gray-900">
        New Apartment Nice View
      </h2>
      <p class="text-gray-500 text-sm">Quincy St, Brooklyn, NY, USA</p>

      <div class="flex justify-between items-center text-gray-700 mt-4 text-sm">
        <div class="flex items-center gap-1">
          <Icon name="mdi:bed-outline" size="20" />
          <span>4 Beds</span>
        </div>
        <div class="flex items-center gap-1">
          <Icon name="mdi:shower" size="20" />
          <span>5 Baths</span>
        </div>
        <div class="flex items-center gap-1">
          <Icon name="mdi:garage" size="20" />
          <span>1 Garage</span>
        </div>
        <div class="flex items-center gap-1">
          <Icon name="mdi:ruler-square" size="20" />
          <span>1200 Sq Ft</span>
        </div>
      </div>

      <div class="mt-5 flex justify-between items-center">
        <div>
          <p class="text-gray-400 line-through text-sm">$2,800/mo</p>
          <p class="text-xl font-bold text-blue-700">$7,500/mo</p>
        </div>
        <div class="flex items-center gap-3 text-gray-600">
          <Icon
            name="mdi:arrow-expand"
            size="22"
            class="cursor-pointer hover:text-blue-700 transition"
          />
          <Icon
            name="mdi:heart-outline"
            size="22"
            class="cursor-pointer hover:text-red-500 transition"
          />
        </div>
      </div>
    </div>
  </div>
</template>

<script setup>
// test


</script>
<style scoped>

</style>
