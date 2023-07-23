<script setup>
import { ref, onMounted } from 'vue';

const cards = [ "A","2","3","4","5","6","7","8","9","10","J","Q","K" ];
const rank = [ "♣", "♦", "♥", "♠" ];
const size = 52;

const score = ref(0);

const piles = [ [], [], [], [] ];

function deal(deck, table) {
}

function move(source, destination) {
}

function shuffle(deck) {
}

function validate(source, destination) {
}

function reset(startWith = 0) {
  score.value = startWith;
}
</script>

<template>
  <slot/>
  <div style="background-color: green; width: 100%;">
    <Deck>
    <Pile v-for"i of 4">
    <Stack v-for"i of 7">
  </div>
</template>

<script scoped>
</script>
