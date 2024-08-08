<template>
  <div
    class="font-body w-screen h-screen flex flex-col items-center px-4 bg-gradient-to-b from-gray-50 to-[#d2d6db]"
  >
    <div
      class="flex flex-col xl:flex-row h-full w-full shadow bg-white rounded-lg px-4 py-6 m-4 gap-12"
    >
      <div class="flex flex-col gap-8 items-center justify-center">
        <div class="flex flex-col gap-4">
          <h1 class="font-semibold text-4xl text-neutral-900 lg:text-5xl">
            Well crafted abstract images
          </h1>
          <span class="font-normal text-lg text-neutral-600 lg:text-xl"
            >High quality abstract images for your projects, wallpaper and
            presentations.</span
          >
        </div>
        <div class="flex flex-row gap-2 lg:gap-8">
          <button
            class="bg-white px-6 rounded h-[48px] w-full lg:w-[213px]  lg:text-lg border-[0.5px] border-solid border-neutral-200"
          >
            Learn more
          </button>
          <button
            class="bg-indigo-600 text-white px-6 rounded h-[48px] w-full lg:w-[213px] lg:text-lg  border-[0.5px] border-solid border-neutral-200"
          >
            See pricing
          </button>
        </div>
      </div>
      <div class="flex items-center justify-center">
        <img src="./assets/hero-image.png" alt="Hero Image" class="w-full h-full max-h-[526px]" />
      </div>
    </div>
  </div>
</template>
