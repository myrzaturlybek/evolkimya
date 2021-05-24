<template>
  <footer class="w-full bg-gray-900">
    <div class="container mx-auto px-4">
      <div class="flex flex-wrap overflow-hidden">
        <div
          class="w-full overflow-hidden py-10 flex justify-center md:justify-start md:w-1/3"
        >
          <img class="w-28" src="../static/logo.png" alt="logo" />
        </div>
        <div
          class="w-full overflow-hidden py-10 flex justify-center md:justify-end md:order-3 md:w-1/3"
        >
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
          class="w-full overflow-hidden py-10 flex justify-center self-center md:order-2 md:w-1/3"
        >
          <span class="text-small text-white"> © 2020 evolkimya </span>
        </div>
      </div>
    </div>
  </footer>
</template>