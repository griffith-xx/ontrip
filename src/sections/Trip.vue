<template>
  <section class="mt-20">
    <h1 class="font-poppins text-center font-medium text-5xl text-black my-16">
      Trip Packages
    </h1>
    <div class="grid grid-cols-3 place-items-center gap-8">
      <div>
        <img
          class="h-[260px] w-full object-cover"
          src="../assets/balos.png"
          alt="balos"
        />
        <div class="bg-white relative h-[180px]">
          <h2 class="font-medium text-[32px] absolute top-4 left-4">
            Greece,<br />
            Balos Beach
          </h2>
          <div
            class="bg-[#425E6F] absolute top-6 right-4 px-3 py-1 w-fit flex items-center gap-1 rounded-md"
          >
            <img class="size-5" src="../assets/star.png" alt="star" />
            <span class="font-medium text-xl text-white"> 4.8K </span>
          </div>
          <span
            class="text-[#425E6F] font-medium text-xl absolute bottom-4 left-4"
            >15,000</span
          >
          <div class="absolute bottom-4 right-4 flex items-center gap-1">
            <img class="size-5" src="../assets/airport.png" alt="airport" />
            <span class="text-[#425E6F] font-medium text-xl">7 Day Trip</span>
          </div>
        </div>
      </div>
      <div class="w-[325px] mx-auto">
        <img
          class="h-[260px] w-full object-cover"
          src="../assets/western.png"
          alt="western"
        />
        <div class="bg-white p-5">
          <h2 class="font-medium text-[32px] mb-3">
            Denmark,<br />
            Western Australia
          </h2>
          <p class="mb-6 text-[#425E6F]/60 font-semibold">
            Travel and find happiness within yourself. Experience holidays in
            Denmark
          </p>

          <div class="flex items-center justify-between">
            <span class="text-[#425E6F] font-medium text-xl">15,000</span>
            <div class="flex items-center gap-1">
              <img class="size-5" src="../assets/airport.png" alt="airport" />
              <span class="text-[#425E6F] font-medium text-xl"
                >15 Day Trip</span
              >
            </div>
          </div>

          <a
            class="bg-[#425E6F] px-4 py-2 text-white font-medium text-xl flex items-center gap-1 w-fit h-fit mt-6 mx-auto"
            href="#"
          >
            <span> Travel Now </span>

            <svg
              xmlns="http://www.w3.org/2000/svg"
              fill="none"
              viewBox="0 0 24 24"
              stroke-width="1.5"
              stroke="currentColor"
              class="size-6"
            >
              <path
                stroke-linecap="round"
                stroke-linejoin="round"
                d="M13.5 4.5 21 12m0 0-7.5 7.5M21 12H3"
              />
            </svg>
          </a>
        </div>
      </div>
      <div>
        <img
          class="h-[260px] w-full object-cover"
          src="../assets/silver.png"
          alt="silver"
        />
        <div class="bg-white relative h-[180px]">
          <h2 class="font-medium text-[32px] absolute top-4 left-4">
            Maldives,<br />
            Silver Beach Resort
          </h2>
          <div
            class="bg-[#425E6F] absolute top-6 right-4 px-3 py-1 w-fit flex items-center gap-1 rounded-md"
          >
            <img class="size-5" src="../assets/star.png" alt="star" />
            <span class="font-medium text-xl text-white"> 4.8K </span>
          </div>
          <span
            class="text-[#425E6F] font-medium text-xl absolute bottom-4 left-4"
            >35,000</span
          >
          <div class="absolute bottom-4 right-4 flex items-center gap-1">
            <img class="size-5" src="../assets/airport.png" alt="airport" />
            <span class="text-[#425E6F] font-medium text-xl">15 Day Trip</span>
          </div>
        </div>
      </div>
    </div>
  </section>
</template>
