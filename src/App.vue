<script setup>
import BaseCard from "@/components/BaseCard.vue";
</script>

<template>
  <div class="content">
    <BaseCard></BaseCard>

    <BaseCard></BaseCard>
  </div>
</template>

<style scoped>
  .content {
    width: 80%;
    display: flex;
    flex-direction: column;
    gap:24px;
  }
</style>
