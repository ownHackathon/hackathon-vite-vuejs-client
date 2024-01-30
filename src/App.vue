<script setup lang="ts">
import { RouterView } from 'vue-router'
import { onMounted } from 'vue'
import { initFlowbite } from 'flowbite'
onMounted(() => {
  initFlowbite();
})
</script>

<template>
  <div class="dark bg-gray-800">
  <RouterView />
  </div>
</template>

<style lang="postcss" scoped>

</style>
