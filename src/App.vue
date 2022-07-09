<script setup lang="ts">
import { defineAsyncComponent } from "vue"
import SplashScreen from "./components/SplashScreen.vue"

const BaseHome = defineAsyncComponent(()=>
  import('@/components/BaseHome.vue')
)
</script>

<template>
  <Suspense>
    <template #default>
      <BaseHome />
    </template>
    <template #fallback>
      <SplashScreen />
    </template>
  </Suspense>
</template>

<style>

</style>
