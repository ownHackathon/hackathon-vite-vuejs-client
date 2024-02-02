<script setup lang="ts">
import LoginIcon from '@/components/icons/LoginIcon.vue'
</script>

<template>
  <header class="antialiased">
    <nav class="bg-white border-gray-200 px-4 lg:px-6 py-2.5 dark:bg-slate-900">
      <div class="flex flex-wrap justify-between items-center">
        <div class="flex justify-start items-center">
          <button id="toggleSidebar" aria-expanded="true" aria-controls="sidebar"
                  class="hidden p-2 mr-3 text-gray-600 rounded cursor-pointer lg:inline hover:text-gray-900 hover:bg-gray-100 dark:text-gray-400 dark:hover:text-white dark:hover:bg-gray-700">
            <svg class="w-5 h-5" aria-hidden="true" xmlns="http://www.w3.org/2000/svg" fill="none" viewBox="0 0 16 12">
              <path stroke="currentColor" stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M1 1h14M1 6h14M1 11h7" />
            </svg>
          </button>
          <button aria-expanded="true" aria-controls="sidebar"
                  class="p-2 mr-2 text-gray-600 rounded-lg cursor-pointer lg:hidden hover:text-gray-900 hover:bg-gray-100 focus:bg-gray-100 dark:focus:bg-gray-700 focus:ring-2 focus:ring-gray-100 dark:focus:ring-gray-700 dark:text-gray-400 dark:hover:bg-gray-700 dark:hover:text-white">
            <svg class="w-[18px] h-[18px]" aria-hidden="true" xmlns="http://www.w3.org/2000/svg" fill="none" viewBox="0 0 17 14">
              <path stroke="currentColor" stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M1 1h15M1 7h15M1 13h15" />
            </svg>
            <span class="sr-only">Toggle sidebar</span>
          </button>
          <a href="/" class="flex mr-4">
            <img src="@/assets/images/hackathon_logo_no_trans.jpeg" class="mr-3 h-8" alt="Hackathon Logo" />
            <span class="self-center text-2xl font-semibold whitespace-nowrap dark:text-white">Hackathon</span>
          </a>
        </div>
        <div class="flex items-center lg:order-2">
          <button type="button" data-dropdown-toggle="notification-dropdown"
                  class="sm:hidden p-2 mr-1 text-gray-500 rounded-lg hover:text-gray-900 hover:bg-gray-100 dark:text-gray-400 dark:hover:text-white dark:hover:bg-gray-700 focus:ring-4 focus:ring-gray-300 dark:focus:ring-gray-600">
            <LoginIcon />
          </button>
          <div class="hidden sm:flex">
            <button type="button">
              <div><span
                class="text-gray-800 dark:text-gray-200 hover:dark:text-lime-400 text-xs bg-slate-900 border-slate-700 border-b border-t  px-10 py-1.5 mr-10">Anmelden</span>
              </div>
            </button>
            <button type="button">
              <div>
                <span class="text-gray-800 dark:text-gray-200 font-bold hover:dark:text-lime-400 subpixel-antialiased  bg-primary-600 rounded-tr-3xl rounded-bl-3xl rounded-br border-t border-b border-primary-500  text-xs px-10 py-1.5 mr-10">
                  Registrieren
                </span>
              </div>
            </button>

          </div>

        </div>
      </div>
    </nav>
  </header>
</template>

<style scoped lang="postcss">

</style>
