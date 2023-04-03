<script setup>
const props = defineProps({
  label: {
    type: String,
    default: 'Button'
  }
})
</script>

<template>
  <button>{{ label }}</button>
</template>
