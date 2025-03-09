<script setup lang="ts">
</script>

<template>
  <header class="shadow bg-sky-50">
    <div class="relative max-w-screen-lg mx-auto py-4 flex sm:items-center sm:justify-between flex-col sm:flex-row">
      
      <NuxtLink class="text-2xl flex items-center font-black" to="/">
        <span class="mr-2 text-3xl text-blue-600">
          <img src="/vmc.png" alt="logo" class="cursor-point rounded-md shadow-sm h-[50px] border border-blue-700">
        </span>
        <span>COMPANY</span>
      </NuxtLink>

      <input class="peer hidden" type="checkbox" id="navbar-open" />
      <label class="cursor-pointer text-xl absolute right-0 mt-1 sm:hidden" for="navbar-open">
        <span class="sr-only">Toggle Navigation</span>
        <Icon name="lucide:align-justify" />
      </label>

      <nav class="peer-checked:block hidden py-4 sm:block sm:py-0">
        <ul class="flex flex-col gap-y-4 sm:gap-x-8 sm:flex-row">
          <li class="">
            <NuxtLink href="" class="text-gray-600 hover:text-blue-600">
              Pricing
            </NuxtLink>
          </li>
          <li class="">
            <NuxtLink href="" class="text-gray-600 hover:text-blue-600">
              Demo
            </NuxtLink>
          </li>
          <li class="">
            <NuxtLink href="" class="text-gray-600 hover:text-blue-600">
              Support
            </NuxtLink>
          </li>
          <li class="mt-2 sm:mt-0">
            <NuxtLink href="" class="border-2 px-6 py-2 rounded-xl border-blue-600 font-medium text-blue-600 hover:bg-blue-600 hover:text-white">
              Login
            </NuxtLink>
          </li>
        </ul>
      </nav>

    </div> 
  </header>
</template>