<script setup lang="ts">

</script>

<template>
  <div class="fixed top-0 left-0 right-0 z-[100000]">
    <div class="flex place-content-center">
      <div class="mt-[25px] xl:mx-[12%] mx-[3%] w-full flex justify-between">
        <div
          class="flex gap-[6px] items-center rounded-[8px] text-[17px] shadow-[0px_0px_2px_0px_#17100e33] lg:bg-white max-[1024px]:backdrop-blur-sm p-[7px]"
        >
          <img src="/Logo.svg" alt="" class="w-[45px] h-[45px]" />
          <div class="hidden lg:flex">
            <RouterLink
              to="/"
              class="p-[12px] font-bold hover:bg-[#abaaa81d] transition-all duration-500 rounded-lg"
              >Product</RouterLink
            >
            <RouterLink
              to="/"
              class="p-[12px] font-bold hover:bg-[#abaaa81d] transition-all duration-500 rounded-lg"
              >Resources</RouterLink
            >
            <RouterLink
              to="/"
              class="p-[12px] font-bold hover:bg-[#abaaa81d] transition-all duration-500 rounded-lg"
              >Pricing</RouterLink
            >
          </div>
        </div>
        <div
          class="flex gap-[12px] items-center rounded-[8px] text-[17px] shadow-[0px_0px_2px_0px_#17100e33] lg:bg-white max-[1024px]:backdrop-blur-sm p-[7px]"
        >
          <div class="hidden lg:flex">
            <RouterLink
              to="/"
              class="p-[12px] font-bold hover:bg-[#abaaa81d] transition-all duration-500 rounded-lg"
              >Contact sales</RouterLink
            >
            <RouterLink
              to="/"
              class="p-[12px] font-bold hover:bg-[#abaaa81d] transition-all duration-500 rounded-lg"
              >Sign in</RouterLink
            >
            <RouterLink
              to="/"
              class="p-[12px] font-bold hover:bg-[#abaaa81d] transition-all duration-500 rounded-lg"
              >View demo</RouterLink
            >
          </div>
          <RouterLink
            to="/"
            class="px-[18px] py-[9px] font-bold hidden lg:flex bg-black text-white rounded-[6px]"
          >
            Start free trial
          </RouterLink>

        </div>
      </div>
    </div>
  </div>
</template>
