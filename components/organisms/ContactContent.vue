<template>
  <div class="contact-content">
    <ContactStanza />
    <Map />
  </div>
</template>

<style lang="scss" scoped>
.contact-content {
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
}
</style>
