<template>
  <div class="home-template">
    <RentCards />
    <SaleCards />
  </div>
</template>

<script lang="ts">
import Vue from 'vue'

export default Vue.extend({
  layout: 'home',
})
</script>

<style lang="scss" scoped>
.home-template {
  display: grid;
  grid-gap: 128px;
  padding-top: 32px;
}
</style>
