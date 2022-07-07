<script setup>
import { VueComponentWith } from "./test.md";
import HelloWorld from "./components/HelloWorld.vue";
const WithHello = VueComponentWith({ HelloWorld });
</script>

<template>
  <article>
    <WithHello />
  </article>
</template>
