<template>
  <div class="w-full bg-pink h-16">
    <div
      class="container mx-auto h-full flex flex-row items-center justify-between px-4"
    >
      <div class="hidden md:block md:w-1/3">
        <nav>
          <ol class="list-none text-white text-lead2 font-semibold">
            <li class="inline"><a href="#about">О нас</a></li>
            <li class="inline mx-8"><a href="#product">Прайс лист</a></li>
            <li class="inline"><a href="#contact">Контакты</a></li>
          </ol>
        </nav>
      </div>
      <div class="flex md:w-1/3 justify-center">
        <img width="120" src="../static/logo.png" alt="logo" />
      </div>
      <div class="hidden md:w-1/3 md:flex md:justify-end">
        <div class="social-media flex">
          <svg
            class="h-8 w-8 text-white mr-4"
            viewBox="0 0 24 24"
            fill="none"
            stroke="currentColor"
            stroke-width="2"
            stroke-linecap="round"
            stroke-linejoin="round"
          >
            <rect x="2" y="2" width="20" height="20" rx="5" ry="5" />
            <path d="M16 11.37A4 4 0 1 1 12.63 8 4 4 0 0 1 16 11.37z" />
            <line x1="17.5" y1="6.5" x2="17.51" y2="6.5" />
          </svg>
          <svg
            class="h-8 w-8 text-white"
            viewBox="0 0 24 24"
            fill="none"
            stroke="currentColor"
            stroke-width="2"
            stroke-linecap="round"
            stroke-linejoin="round"
          >
            <path
              d="M18 2h-3a5 5 0 0 0-5 5v3H7v4h3v8h4v-8h3l1-4h-4V7a1 1 0 0 1 1-1h3z"
            />
          </svg>
        </div>
      </div>
      <div
        @click="mobileMenuOpened = true"
        class="menu-burger md:hidden cursor-pointer"
      >
        <svg
          class="h-10 w-10 text-white"
          viewBox="0 0 24 24"
          fill="none"
          stroke="currentColor"
          stroke-width="2"
          stroke-linecap="round"
          stroke-linejoin="round"
        >
          <line x1="3" y1="12" x2="21" y2="12" />
          <line x1="3" y1="6" x2="21" y2="6" />
          <line x1="3" y1="18" x2="21" y2="18" />
        </svg>
      </div>
      <!-- Mobile menu -->
      <div
        v-show="mobileMenuOpened"
        class="mobile-menu absolute top-0 bg-pink px-2 inset-x-0 md:hidden"
      >
        <div
          @click="mobileMenuOpened = false"
          class="flex h-16 items-center justify-end cursor-pointer"
        >
          <svg
            class="h-10 w-10 text-white"
            fill="none"
            viewBox="0 0 24 24"
            stroke="currentColor"
          >
            <path
              stroke-linecap="round"
              stroke-linejoin="round"
              stroke-width="2"
              d="M6 18L18 6M6 6l12 12"
            />
          </svg>
        </div>
        <div class="pt-3 pb-6">
          <nav>
            <ol class="list-none text-white text-h3 font-semibold">
              <li class="text-center my-4"><a href="#about">О нас</a></li>
              <li class="text-center my-4">
                <a href="#product">Прайс лист</a>
              </li>
              <li class="text-center my-4"><a href="#contact">Контакты</a></li>
            </ol>
          </nav>
        </div>
        <div class="pb-4 flex justify-center">
          <svg
            class="h-8 w-8 text-white mr-4"
            viewBox="0 0 24 24"
            fill="none"
            stroke="currentColor"
            stroke-width="2"
            stroke-linecap="round"
            stroke-linejoin="round"
          >
            <rect x="2" y="2" width="20" height="20" rx="5" ry="5" />
            <path d="M16 11.37A4 4 0 1 1 12.63 8 4 4 0 0 1 16 11.37z" />
            <line x1="17.5" y1="6.5" x2="17.51" y2="6.5" />
          </svg>
          <svg
            class="h-8 w-8 text-white"
            viewBox="0 0 24 24"
            fill="none"
            stroke="currentColor"
            stroke-width="2"
            stroke-linecap="round"
            stroke-linejoin="round"
          >
            <path
              d="M18 2h-3a5 5 0 0 0-5 5v3H7v4h3v8h4v-8h3l1-4h-4V7a1 1 0 0 1 1-1h3z"
            />
          </svg>
        </div>
      </div>
    </div>
  </div>
</template>
<script>
export default {
  data() {
    return {
      mobileMenuOpened: false,
    };
  },
};
</script>