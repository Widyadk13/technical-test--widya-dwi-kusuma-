<template>
  <div class="relative overflow-hidden bg-white">
    <div class="mx-auto max-w">
      <div class="relative z-10 bg-white pb-8 sm:pb-16 md:pb-20 lg:w-full lg:max-w-2xl lg:pb-28 xl:pb-32">
        <svg class="absolute inset-y-0 right-0 hidden h-full w-48 translate-x-1/2 transform text-white lg:block" fill="currentColor" viewBox="0 0 100 100" preserveAspectRatio="none" aria-hidden="true">
          <polygon points="50,0 100,0 50,100 0,100" />
        </svg>

        <Popover>
          <div class="relative px-4 pt-6 sm:px-6 lg:px-8">
            <nav class="relative flex items-center justify-between sm:h-10 lg:justify-start" aria-label="Global">
              <div class="flex flex-shrink-0 flex-grow items-center lg:flex-grow-0">
              </div>
              <div class="hidden md:ml-10 md:block md:space-x-8 md:pr-4">
                <a v-for="item in navigation" :key="item.name" :href="item.href" class="font-medium text-gray-500 hover:text-gray-900">{{ item.name }}</a>
                <a href="#" class="font-medium text-indigo-600 hover:text-indigo-500"></a>
              </div>
            </nav>
          </div>
        </Popover>

        <main class="mx-auto mt-10 max-w-7xl px-4 sm:mt-12 sm:px-6 md:mt-16 lg:mt-20 lg:px-8 xl:mt-28">
          <h1 class="text-2xl text-Interstate-Regular sm:justify-center">Sistem Informasi Akademik</h1>
          <div class="sm:text-center lg:text-left">
            <h1 class="text-24px font-bold tracking-tight text-gray-900 sm:text-5xl md:text-6xl">
              <span class="text-24px block xl:inline text-tranform:uppercase j">Universitas Terbuka</span>
              {{ ' ' }}
            </h1>
            <p class="mt-3 text-base text-gray-500 sm:mx-auto sm:mt-5 sm:max-w-xl sm:text-lg md:mt-5 md:text-xl lg:mx-0"></p>
            <div class="mt-5 sm:mt-8 sm:flex sm:justify-center lg:justify-start">
            </div>
          </div>
        </main>
      </div>
    </div>
    <div class="lg:absolute lg:inset-y-0 lg:right-0 lg:w-1/2">
      <img class="w-full object-cover lg:w-100" src="https://admisi-sia.ut.ac.id/img/bg-login-2.04081f4b.png" alt="" />
    </div>
  </div>

  
    
</template>

<script setup>
import { Popover, PopoverButton, PopoverPanel } from '@headlessui/vue'
import { Bars3Icon, XMarkIcon } from '@heroicons/vue/24/outline'

const navigation = [
  { name: 'Branda', href: '#' },
  { name: 'Informasi', href: '#' },
  { name: 'Aplikasi UT Lainnya', href: '#' },
]
</script>

@media (min-width: 640px)
<style>
.sm\:justify-center {
    justify-content: center;
}

.text-2xl {
  font-size: 1.5rem;
  line-height: 2rem;
}

.text-center {
  text-align: center;
}

/* form */
.px-2 {
    padding-left: 0.5rem;
    padding-right: 0.5rem;
}

.bg-white {
    --tw-bg-opacity: 1;
    background-color: rgba(255,255,255,var(--tw-bg-opacity));
}

</style>