<template>
  <div class="rent-cards">
    <Title :text="'Máquinas para aluguel'" />
    <RentCardsContent />
  </div>
</template>

<script lang="ts">
import Vue from 'vue'

export default Vue.extend({
  layout: 'home',
})
</script>

<style lang="scss" scoped>
.rent-cards {
  display: grid;
}
</style>
