<!-- src/components/WhiteCard.vue -->
<template>
  <div class="space-y-4">
    <h2 class="text-xl font-semibold text-gray-800">{{ title }}</h2>
    <div class="white-card">
      <slot />
    </div>
  </div>
</template>

<script>
export default {
  props: {
    title: {
      type: String,
      required: true
    }
  }
}
</script>