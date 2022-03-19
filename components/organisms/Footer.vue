<template>
  <footer class="footer">
    <Logo />
    <ul class="items">
      <li class="item">
        <SocialLinks />
      </li>
    </ul>
  </footer>
</template>

<style lang="scss" scoped>
footer {
  /* Auto layout */
  display: flex;
  flex-direction: row;
  justify-content: space-between;
  align-items: center;
  padding: 40px 64px;

  position: static;
  width: 100%;
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
}
</style>
