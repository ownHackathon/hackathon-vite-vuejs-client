<script setup lang="ts">
import { RouterView } from 'vue-router'
import { onMounted } from 'vue'
import { initFlowbite } from 'flowbite'
import HeaderNavigation from '@/components/header/HeaderNavigation.vue'
import Footer from '@/components/Footer.vue'
onMounted(() => {
  initFlowbite();
})
</script>

<template>
  <div class="dark">
    <HeaderNavigation />
    <RouterView />
    <Footer />
  </div>
</template>

<style lang="scss" scoped>

</style>
