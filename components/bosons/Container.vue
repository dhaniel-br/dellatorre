<template>
  <div class="container">
    <slot />
  </div>
</template>

<style lang="scss" scoped>
.container {
  max-width: 1fr;
  margin: 0px auto;
  padding: 0px 32px;
  @include screen('infinity', 'large') {
    width: 100%;
  }
  @include screen('medium') {
    width: 85%;
    align-items: center;
  }
  @include screen('small') {
    width: 90%;
  }
}
</style>
