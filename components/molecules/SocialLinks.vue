<template>
  <div class="social-links">
    <a
      class="social-link"
      href="tel:633015-2222"
      target="_blank"
      rel="zapzap dellatorre"
    >
      <img src="@/assets/icons/phone-line.svg" alt="whatsapp-dellatorre" />
      (63) 3015-2222
    </a>
    <a
      class="social-link"
      href="https://api.whatsapp.com/send/?phone=5563992212929&text=Olá, tudo bem? Estou vindo do site da Dellatorre!&app_absent=0"
      target="_blank"
      rel="zapzap dellatorre"
    >
      <img src="@/assets/icons/whatsapp-line.svg" alt="whatsapp-dellatorre" />
      (63) 9 9221-2929
    </a>
  </div>
</template>

<style lang="scss" scoped>
.social-links {
  display: flex;
  flex-direction: row;
  justify-content: center;
  align-items: center;

  gap: 32px;

  .social-link {
    display: flex;
    flex-direction: row;
    justify-content: center;
    align-items: center;
    gap: 8px;

    color: color(neutral, 'light');
  }
}
</style>
