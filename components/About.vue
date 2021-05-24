<template>
  <div id="about" class="about w-full bg-pink py-16 md:bg-white">
    <div class="container mx-auto px-4 md:flex">
      <div
        class="hidden md:flex md:bg-pink md:items-center md:justify-center md:w-1/2 md:rounded-md md:py-44"
      >
        <img class="md:w-4/5 max-w-md" src="../static/logo.png" alt="logo" />
      </div>
      <div
        class="text-white md:text-black md:w-1/2 md:flex md:flex-col md:justify-center md:pl-10"
      >
        <h2 class="text-h2 font-extrabold mb-12">О нас</h2>
        <p class="text-lead1">
          Как химический завод, созданный в Измире, Эвол Кимья с 25-летним
          опытным техническим персоналом производит системы защитного и
          декоративного покрытия для бетонных, деревянных и стальных
          поверхностей.
        </p>
        <div class="mt-9">
          <a href="#contact">
            <Button color="text-pink" bg="bg-pink-800" text="Связаться" />
          </a>
        </div>
      </div>
    </div>
  </div>
</template>