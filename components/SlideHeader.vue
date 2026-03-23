<template>
  <div class="slide-header">
    <span class="slide-header-title">{{ title }}</span>
    <span class="slide-header-counter">{{ counter }}</span>
  </div>
  <div class="slide-content">
    <slot />
  </div>
</template>

<script setup>
defineProps({
  title: String,
  counter: String,
})
</script>
