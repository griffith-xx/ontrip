<template>
  <section class="mt-32">
    <h1 class="font-poppins text-center font-medium text-5xl text-black my-6">
      What Travelers Are Saying
    </h1>
    <p class="italic text-center mx-auto text-3xl text-black/70 tracking-wide">
      “I am a traveler and ON TRIP Travels helps me a lot <br />
      in finding interesting tourist destinations and of <br />
      course the price offers is very worth it”.
    </p>
    <div class="grid grid-cols-2 mt-20 gap-10">
      <div
        class="bg-white px-6 py-4 shadow-lg flex justify-center items-center gap-6"
      >
        <img class="size-[125px]" src="../assets/smith.png" alt="smith" />
        <div>
          <h2 class="text-2xl">Emily Smith</h2>
          <div class="flex items-center gap-1">
            <img
              v-for="i in Number(5)"
              class="size-5"
              src="../assets/star-gold.png"
              alt="star gold"
            />
          </div>
          <p class="tracking-wide mt-4">
            Good trip. The team of ON TRIP tours and <br />
            travel was very supportive and maintained prompt communication with
            us .
          </p>
        </div>
      </div>
      <div
        class="bg-white px-6 py-4 shadow-lg flex justify-center items-center gap-6"
      >
        <img class="size-[125px]" src="../assets/martin.png" alt="martin" />
        <div>
          <h2 class="text-2xl">Lord Martin</h2>
          <div class="flex items-center gap-1">
            <img
              v-for="i in Number(5)"
              class="size-5"
              src="../assets/star-gold.png"
              alt="star gold"
            />
          </div>
          <p class="tracking-wide mt-4">
            Good trip. The team of ON TRIP tours and <br />
            travel was very supportive and maintained prompt communication with
            us .
          </p>
        </div>
      </div>
    </div>
  </section>
</template>
