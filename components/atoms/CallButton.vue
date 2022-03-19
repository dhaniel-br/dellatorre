<template>
  <div>
    <a class="call-button" href="tel:633015-2222" target="_blank">
      <img
        class="whatsapp-icon"
        src="@/assets/icons/phone-fill.svg"
        alt="icon"
      />
      Ligar agora
    </a>
  </div>
</template>

<style lang="scss" scoped>
.call-button {
  display: flex;
  flex-direction: row;
  justify-content: center;
  align-items: center;
  padding: 12px;
  gap: 8px;
  width: 156px;
  height: 48px;

  border: 2px solid color(primary);
  box-sizing: border-box;
  border-radius: 8px;

  color: color(primary);
}
</style>
