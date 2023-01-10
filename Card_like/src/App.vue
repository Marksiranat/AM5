<script setup>
import LikeSad from "./components/LikeSad.vue";
import IMG from "./components/img.vue";
</script>

<template>
  <div class="container">
    <div class="row justify-content-center">
      <div v-for="n in 6" :key="n" class="col-4">
        {{ n }}
        <IMG></IMG>
        <LikeSad></LikeSad>
      </div>
    </div>
  </div>
</template>

<style></style>
