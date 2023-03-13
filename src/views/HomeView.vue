<template>
  <main class="relative h-screen">
    <section class="relative flex flex-col justify-center items-center z-0 h-full">
      <h1
        class="stretch text-6xl font-bold text-center w-full text-neutral-900"
      >
        THIS IS YOUR WAY <br />
        TO ALL WHAT YOU <br />
        NEED
      </h1>
      <img
        class="hidden lg:block absolute right-64 top-1/2 -translate-y-1/3 -z-20"
        src="../assets/images/arrow.svg"
        alt="Arrow"
      />
      <router-link
        title="Portfolio"
        to="/portfolio"
        class="poppins font-semibold text-white text-xl uppercase mt-28 px-10 py-3.5 rounded-2xl bg-neutral-900 hover:bg-neutral-800 ease-in-out duration-200 focus:bg-white focus:text-black"
      >
        GET STARTED
      </router-link>
    </section>
  </main>
</template>

<style scoped>
main {
  background: url("../assets/images/bg-image.png") no-repeat;
  background-size: cover;
}
</style>
