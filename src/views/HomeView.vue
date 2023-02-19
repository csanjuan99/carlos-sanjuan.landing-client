<script setup>
import AppBackgroundComponent from "@/components/background/AppBackgroundComponent.vue";
</script>

<template>
  <main class="relative">
    <section
      class="absolute top-1/2 left-1/2 z-10 -translate-x-1/2 -translate-y-1/2 flex flex-col items-center z-0"
    >
      <h1
        class="stretch text-6xl font-bold text-center w-full text-neutral-900"
      >
        THIS IS YOUR WAY <br />
        TO ALL WHAT YOU <br />
        NEED
      </h1>
      <img
        class="hidden lg:block absolute -right-32 top-10 -z-20"
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
    <app-background-component />
  </main>
</template>

<style scoped></style>
