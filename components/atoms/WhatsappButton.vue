<template>
  <div>
    <a
      class="whatsapp-button"
      href="https://api.whatsapp.com/send/?phone=5563992212929&text=Olá, tudo bem? Estou vindo do site da Dellatorre!&app_absent=0"
      target="_blank"
    >
      <img
        class="whatsapp-icon"
        src="@/assets/icons/whatsapp-fill.svg"
        alt="icon"
      />
      {{ text }}
    </a>
  </div>
</template>

<script lang="ts">
import vue from 'vue'

export default vue.extend({
  props: {
    text: {
      type: String,
      required: true,
    },
  },
})
</script>

<style lang="scss" scoped>
.whatsapp-button {
  display: flex;
  flex-direction: row;
  justify-content: center;
  align-items: center;
  padding: 12px;
  gap: 8px;
  width: 158px;

  border-radius: 8px;

  background-color: color(primary);
  color: color(backcolors, 'dark');
}
</style>
