<template>
  <header>
    <Logo />
    <nav>
      <ul class="items">
        <li class="item">
          <NuxtLink to="/">ínicio</NuxtLink>
        </li>
        <li class="item">
          <NuxtLink to="/sobre-nos">sobre nós</NuxtLink>
        </li>
        <li class="item">
          <NuxtLink to="/contato">contato</NuxtLink>
        </li>
      </ul>
    </nav>
  </header>
</template>

<script lang="ts">
import Vue from 'vue'

export default Vue.extend({})
</script>

<style lang="scss" scoped>
header {
  /* Auto layout */
  display: flex;
  flex-direction: row;
  justify-content: space-between;
  align-items: center;

  padding: 40px 32px;

  position: static;
  height: 128px;

  /* Neutral/Preto */
  background: color(backcolors, 'light');

  @include screen('small') {
    display: flex;
    flex-direction: column;
    justify-content: space-between;
    gap: 16px;
    padding: 24px 0px 16px 0px;
  }

  .items {
    display: grid;
    grid-template-columns: repeat(3, auto);
    align-items: center;
    grid-gap: 32px;
    justify-content: space-around;
    height: 100%;
  }
  .item a {
    color: #fff;
    position: relative;
    font-weight: 500;
    display: flex;
    &.nuxt-link-exact-active:after {
      content: '';
      position: absolute;
      width: 100%;
      height: 4px;
      background: color(primary);
      bottom: -16px;
      align-content: center;
    }
  }
}
</style>
