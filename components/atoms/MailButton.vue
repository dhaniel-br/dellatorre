<template>
  <div>
    <a
      class="mail-button"
      href="mailto:grupodellatorre@gmail.com"
      target="_blank"
    >
      <img
        class="whatsapp-icon"
        src="@/assets/icons/mail-fill.svg"
        alt="icon"
      />
      Enviar um email
    </a>
  </div>
</template>

<style lang="scss" scoped>
.mail-button {
  display: flex;
  flex-direction: row;
  justify-content: center;
  align-items: center;
  padding: 12px;
  gap: 8px;
  width: 178px;

  border-radius: 8px;

  background-color: #ff3d3d;
  color: color(neutral, 'light');
}
</style>
