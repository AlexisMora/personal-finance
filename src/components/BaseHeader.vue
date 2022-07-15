<script setup lang="ts">
  const reload = function() {
    location.reload()
  }
</script>

<template>
  <header
    class=" flex flex-row justify-around items-center w-full"
  >
    <div class="flex flex-row justify-between items-center">
      <img
        src="@/assets/logo.svg"
        alt="pfa_logo"
        class="w-12"
        @click="reload"
      >
      <h1 class="text-blue-400 text-center mt-11 text-xl font-bold mb-8 ml-6">
        Personal Finance App
      </h1>
      <span class="w-12" />
    </div>
  </header>
</template>

