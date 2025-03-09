<script setup lang="ts">
</script>

<template>
  <section class="relative flex flex-col py-16 lg:pt-0 lg:flex-col lg:pb-0">
    <div class="flex flex-col items-start w-full max-w-xl px-4 mx-auto lg:px-8 lg:max-w-screen-xl">
      <div class="mb-16 lg:my-40 lg:max-w-lg lg:pr-5">
        <div class="max-w-xl mb-6">
          <div>
            <p class="inline-block px-3 py-px mb-4 text-xs font-semibold tracking-wider text-teal-900 uppercase rounded-full bg-teal-400">
              New Colaboration
            </p>
          </div>
          <h2 class="max-w-lg mb-6 font-sans text-3xl font-bold tracking-tight text-gray-900 sm:text-4xl sm:leading-none">
            Empowering innovation, <br class="hidden md:block" />
            delivering excellence
            <span class="inline-block text-blue-400">every step of the way.</span>
          </h2>
          <p class="text-base text-gray-700 md:text-lg">
            At our company, we turn ideas into impact, crafting solutions that inspire progress and drive success for a brighter future.
          </p>
        </div>
        <div class="flex flex-col items-center md:flex-row">
          <a
            href="/"
            class="inline-flex items-center justify-center w-full h-12 px-6 mb-3 font-medium tracking-wide text-white transition duration-200 rounded shadow-md md:w-auto md:mr-4 md:mb-0 bg-blue-400 hover:bg-blue-700 focus:shadow-outline focus:outline-none"
          >
            Apply Now
          </a>
          <a href="/" aria-label="" class="inline-flex items-center font-semibold text-gray-800 transition-colors duration-200 hover:text-blue-700">Learn more</a>
        </div>
      </div>
    </div>
    <div class="inset-y-0 right-0 w-full max-w-xl px-4 mx-auto lg:pl-8 lg:pr-0 lg:mb-0 lg:mx-0 lg:w-1/2 lg:max-w-full lg:absolute xl:px-0">
      <img
        class="object-cover w-full h-56 rounded shadow-lg lg:rounded-none lg:shadow-none sm:h-96 lg:h-full"
        src="https://images.pexels.com/photos/3184287/pexels-photo-3184287.jpeg?auto=compress&amp;cs=tinysrgb&amp;dpr=2&amp;h=750&amp;w=1260"
        alt=""
      />
    </div>
  </section>
</template>