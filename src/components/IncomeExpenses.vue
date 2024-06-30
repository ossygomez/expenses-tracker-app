<template lang="html">
  <div class="inc-exp-container">
      <div class="">
        <h4>Income</h4>
        <p id="money-plus" class="money-plus">+${{ income }}</p>
      </div>
      <div class="">
        <h4>Expenses</h4>
        <p id="money-minus" class="money-minus">${{ expenses }}</p>
      </div>
  </div>
</template>

<script setup>
  import { defineProps} from 'vue'

  const props = defineProps({
    income: {
      type: Number,
      required: true
    },
    expenses: {
      type: Number,
      required: true
    }
  })
</script>

<style lang="css" scoped>
</style>
