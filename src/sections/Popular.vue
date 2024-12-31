<template>
  <section class="mt-32">
    <h1 class="font-poppins text-center font-medium text-5xl text-black my-16">
      Most Popular Destinations
    </h1>
    <div class="grid grid-cols-10 gap-6">
      <div class="col-span-7">
        <div class="grid grid-cols-2 gap-6">
          <div class="col-span-2 relative">
            <img
              class="w-full object-cover"
              src="../assets/switzerland.png"
              alt="switzerland"
            />
            <span
              class="absolute bottom-1 left-1/2 -translate-x-1/2 text-[40px] text-white inner_text_shadow"
            >
              Switzerland
            </span>
          </div>
          <div class="relative">
            <img
              class="w-full object-cover"
              src="../assets/spain.png"
              alt="spain"
            />
            <span
              class="absolute bottom-1 left-1/2 -translate-x-1/2 text-[40px] text-white inner_text_shadow"
            >
              Spain
            </span>
          </div>
          <div class="relative">
            <img
              class="w-full object-cover"
              src="../assets/london.png"
              alt="london"
            />
            <span
              class="absolute bottom-1 left-1/2 -translate-x-1/2 text-[40px] text-white inner_text_shadow"
            >
              London
            </span>
          </div>
        </div>
      </div>
      <div class="col-span-3 grid grid-cols-1 gap-6">
        <div class="relative">
          <img
            class="w-full object-cover h-full rounded-2xl"
            src="../assets/maldives.png"
            alt="maldives"
          />
          <span
            class="absolute bottom-2 left-1/2 -translate-x-1/2 text-[40px] text-white inner_text_shadow"
          >
            Maldives
          </span>
        </div>
        <div class="relative">
          <img
            class="w-full object-cover h-full rounded-2xl"
            src="../assets/greece.png"
            alt="greece"
          />
          <span
            class="absolute bottom-2 left-1/2 -translate-x-1/2 text-[40px] text-white inner_text_shadow"
          >
            Greece
          </span>
        </div>
        <div class="relative">
          <img
            class="w-full object-cover h-full rounded-2xl"
            src="../assets/bali.png"
            alt="bali"
          />
          <span
            class="absolute bottom-2 left-1/2 -translate-x-1/2 text-[40px] text-white inner_text_shadow"
          >
            Bali
          </span>
        </div>
      </div>
    </div>
  </section>
</template>
