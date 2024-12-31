<template>
  <section>
    <div class="bg relative">
      <div class="font-poppins h-[1000px] relative">
        <h2
          class="text-[#E7F6FF] text-[76px] font-medium inner_text_shadow absolute top-[150px] left-1/2 -translate-x-1/2"
        >
          Let's Make your
        </h2>
        <h2
          class="text-[#E7F6FF] text-[76px] font-medium inner_text_shadow absolute top-[250px] left-1/2 -translate-x-[10%]"
        >
          Dream Vacation
        </h2>
      </div>
      <div
        class="absolute left-1/2 -translate-x-1/2 bottom-10 w-[1200px] h-[75px] bg-gradient-to-r from-[#E2EBF0] to-[#C0D9E7] rounded-[20px] flex items-center justify-between px-4"
      >
        <div class="flex items-start gap-2">
          <img
            class="size-[34px] mt-1"
            src="../assets/location-2.png"
            alt="location"
          />
          <div class="flex flex-col">
            <h3 class="font-bold text-xl">Location</h3>
            <p class="text-black/60">Where do you want to go?</p>
          </div>
        </div>
        <div class="flex items-start gap-2">
          <img
            class="size-[26px] mt-1"
            src="../assets/calendar.png"
            alt="calender"
          />
          <div class="flex flex-col">
            <h3 class="font-bold text-xl">Date</h3>
            <p class="text-black/60">Choose Date</p>
          </div>
        </div>
        <div class="flex items-start gap-2">
          <img class="size-[26px] mt-1" src="../assets/bill.png" alt="bill" />
          <div class="flex flex-col">
            <h3 class="font-bold text-xl">Pricing</h3>
            <p class="text-black/60">Choose Your budget</p>
          </div>
        </div>
        <a
          class="bg-[#425E6F] rounded-[20px] px-5 py-2 text-white text-[20px] font-medium flex h-fit"
          href="#"
        >
          <img
            class="size-[24px]"
            src="../assets/location-1.png"
            alt="locatino"
          />
          <span class="ml-2"> Explore </span>
          <span class="ml-2"> Now </span>
        </a>
      </div>
    </div>
  </section>
</template>

<style>
.bg {
  min-height: 1000px;
  background-image: url("../assets/bg.png");
  background-repeat: no-repeat;
  background-size: cover;
}
</style>
