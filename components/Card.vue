 19 lines (16 sloc) 384 Bytes
<script setup>
import { ref, onMounted } from 'vue';

const props = defineProps({
  value: {
    type: Number,
    default: 0
  },
  rank: {
    type: String
  }
});
</script>

<template>
  <div style="background-color: white; width: 100%; border-radius: 10px;">
    <slot></slot>
  </div>
</template>

<script scoped>
</script>
