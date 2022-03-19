<template>
  <div class="banner">
    <div class="texts">
      <Title text="Compra, venda e aluguel" />
      <p>de máquinas pesadas</p>
    </div>
    <img
      class="background"
      src="@/assets/images/background.png"
      alt="background"
    />
  </div>
</template>

<style lang="scss" scoped>
.banner {
  display: block;
  height: 100%;
  width: 100%;
  .texts {
    position: absolute;
    margin-top: 32px;
    left: 32px;
    color: color(neutral, 'light');
    @include screen('small') {
      left: 32px;
    }
  }
  .background {
    width: 100%;
  }
}
</style>
