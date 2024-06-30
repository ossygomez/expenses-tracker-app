<template lang="html">
  <h4>Your Balance</h4>
  <h1 id="balance">${{ total }}</h1>
</template>

<script setup>
  import { defineProps } from 'vue'

  const props = defineProps({
    total: {
      type: Number,
      required: true
    }
  })
</script>

<style lang="css" scoped>
</style>
