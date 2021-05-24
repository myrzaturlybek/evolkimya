<template>
  <div class="hero w-full py-14">
    <div class="container mx-auto px-4 flex md:pt-44 md:pb-32">
      <div class="flex flex-col justify-center">
        <h1 class="text-h1 font-extrabold text-center md:text-left">
          Evol Kimya
        </h1>
        <p class="text-lead1 text-center mt-3 mb-8 md:text-left md:pr-3">
          Новое дыхание на бетонных, деревянных и стальных поверхностях!
        </p>
        <a href="#contact">
          <Button
            class="self-center md:self-start"
            text="Связаться"
            bg="bg-pink"
            color="text-white"
          />
        </a>
      </div>
      <div class="hidden md:block md:flex-grow md:flex md:justify-center">
        <img src="../static/hero.png" alt="hero" />
      </div>
    </div>
  </div>
</template>

<style scoped>
.hero {
  background-image: url("data:image/svg+xml,%3Csvg%20width%3D%22345%22%20height%3D%22414%22%20viewBox%3D%220%200%20345%20414%22%20fill%3D%22none%22%20xmlns%3D%22http%3A%2F%2Fwww.w3.org%2F2000%2Fsvg%22%3E%0A%3Ccircle%20cx%3D%2244%22%20cy%3D%22326%22%20r%3D%2226%22%20fill%3D%22%2375E3EA%22%2F%3E%0A%3Ccircle%20cx%3D%2226%22%20cy%3D%22114%22%20r%3D%2226%22%20fill%3D%22%23FFC278%22%2F%3E%0A%3Cellipse%20cx%3D%22238%22%20cy%3D%22202.5%22%20rx%3D%22238%22%20ry%3D%22211.5%22%20fill%3D%22%23F0C3E8%22%2F%3E%0A%3C%2Fsvg%3E");
  background-repeat: no-repeat;
  background-position: 100% -65px;
}
@media (min-width: 768px) {
  .hero {
    background-image: url("data:image/svg+xml,%3Csvg%20width%3D%22698%22%20height%3D%22648%22%20viewBox%3D%220%200%20698%20648%22%20fill%3D%22none%22%20xmlns%3D%22http%3A%2F%2Fwww.w3.org%2F2000%2Fsvg%22%3E%0A%3Ccircle%20cx%3D%22314%22%20cy%3D%2236%22%20r%3D%2236%22%20fill%3D%22%232EC5CE%22%2F%3E%0A%3Ccircle%20cx%3D%2236%22%20cy%3D%22251%22%20r%3D%2236%22%20fill%3D%22%23FE9A22%22%2F%3E%0A%3Ccircle%20cx%3D%22458%22%20cy%3D%22370%22%20r%3D%22370%22%20fill%3D%22%239C2686%22%2F%3E%0A%3C%2Fsvg%3E%0A");
    background-repeat: no-repeat;
    background-position: 100% 218px;
  }
}
</style>