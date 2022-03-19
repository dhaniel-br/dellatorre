<template>
  <div class="sale-cards">
    <Title :text="'Máquinas à venda'" />
    <SaleCardsContent />
  </div>
</template>

<script lang="ts">
import Vue from 'vue'

export default Vue.extend({
  layout: 'home',
})
</script>

<style lang="scss" scoped>
.sale-cards {
  display: grid;
}
</style>
