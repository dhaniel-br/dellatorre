<template>
  <div class="presentation">
    <AboutStanza />
    <img src="@/assets/images/aside.png" alt="" srcset="" />
  </div>
</template>

<style lang="scss" scoped>
.presentation {
  display: grid;
  grid-template-columns: repeat(2, 1fr);

  grid-gap: 2rem;
  margin-top: 64px;

  @include screen('small', 'medium') {
    grid-template-columns: 1fr;
  }
  p {
    line-height: 26px;
  }
  img {
    max-width: 100%;
  }
}
</style>
