<script setup>
import MainCardSingle from './MainCardSingle.vue';
</script>

<template>
    <div class="grid grid-cols-4 gap-8 p-10">
  <MainCardSingle v-for="card in 20"></MainCardSingle>
    </div>
</template>

