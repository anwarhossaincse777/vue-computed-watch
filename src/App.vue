<script setup>
import Fruits from './components/Fruits.vue';
import CartComputedFruit from "./components/Cart-computed-Fruit.vue";
import PriceWithout_computed from "./components/Price-Without_computed.vue";
import WatchPost from "./components/watch-post.vue";
</script>

<template>
<!--  <Fruits/>-->

<!--  <CartComputedFruit/>-->

<!--  <PriceWithout_computed/>-->

  <watch-post/>
</template>

<style scoped>
.logo {
  height: 6em;
  padding: 1.5em;
  will-change: filter;
  transition: filter 300ms;
}
.logo:hover {
  filter: drop-shadow(0 0 2em #646cffaa);
}
.logo.vue:hover {
  filter: drop-shadow(0 0 2em #42b883aa);
}
</style>
