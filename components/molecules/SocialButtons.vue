<template>
  <div class="social-buttons">
    <div class="stanza">
      <WhatsappButton :text="'Whatsapp'" />
      <p class="sub-title">(63) 9 9221-2929</p>
    </div>
    <div class="stanza">
      <CallButton />
      <p class="sub-title">(63) 3015-2222</p>
    </div>
    <div class="stanza">
      <MailButton />
      <p class="sub-title">grupodellatorre@gmail.com</p>
    </div>
  </div>
</template>

<style lang="scss" scoped>
.social-buttons {
  display: flex;
  flex-direction: column;
  align-items: flex-start;
  gap: 32px;

  .stanza {
    display: flex;
    flex-direction: column;
    align-items: flex-start;
    gap: 8px;

    .sub-title {
      font-size: 10pt;
      font-weight: 100;

      color: color(neutral, 'light');
    }
  }
}
</style>
