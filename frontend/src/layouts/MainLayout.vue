<!-- src/layouts/MainLayout.vue -->
<template>
  <div class="min-h-screen bg-gray-100">
    <GNB />
    <main class="p-10">
      <div class="flex space-x-10">
        <div class="w-1/2">
          <slot name="left" />
        </div>
        <div class="w-1/2">
          <slot name="right" />
        </div>
      </div>
    </main>
  </div>
</template>

<script>
import GNB from '@/components/GNB.vue'

export default {
  components: { GNB }
}
</script>