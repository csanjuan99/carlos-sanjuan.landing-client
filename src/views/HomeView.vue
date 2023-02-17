<script setup>
import AppBackgroundComponent from "@/components/background/AppBackgroundComponent.vue";
</script>

<template>
  <main class="relative">
    <section class="xl:absolute top-1/2 left-1/2 z-10 -translate-x-1/2 -translate-y-1/2 flex flex-col items-center">
      <h1
        class="stretch text-6xl font-bold text-center w-full text-neutral-900"
      >
        THIS IS YOUR WAY <br />
        TO ALL WHAT YOU <br />
        NEED
      </h1>
      <router-link
        to="/portfolio"
        class="poppins font-semibold text-white uppercase border border-transparent ease-in-out duration-200 hover:border-b-white focus:text-neutral-900 foucs:border-b-neutral-900 mt-10"
      >
        Portfolio
      </router-link>
    </section>
    <app-background-component />
  </main>
</template>

<style scoped>
</style>
