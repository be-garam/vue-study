<!-- src/components/CustomInput.vue -->
<template>
  <input
    :type="type"
    :value="modelValue"
    @input="$emit('update:modelValue', $event.target.value)"
    class="custom-input"
    v-bind="$attrs"
  >
</template>

<script>
export default {
  props: {
    modelValue: String,
    type: {
      type: String,
      default: 'text'
    }
  }
}
</script>