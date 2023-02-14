<script setup>
import { ref, onMounted } from 'vue';

const cards = [ "A","2","3","4","5","6","7","8","9","10","J","Q","K" ];
const rank = [ "♣", "♦", "♥", "♠" ];
const size = 52;
</script>

<template>
  <slot/>
  <div style="background-color: green; width: 100%;">
  </div>
</template>

<script scoped>
</script>
