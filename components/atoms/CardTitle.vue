<template>
  <div>
    <h1 class="title">
      {{ text }}
    </h1>
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
.title {
  font-family: Inter;
  font-size: 14pt;
  font-weight: 800;
  text-transform: uppercase;
  text-transform: uppercase;

  height: 24px;

  color: color(neutral, 'light');
}
</style>
