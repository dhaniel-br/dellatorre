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
  font-family: Redwing;
  font-size: 24pt;
  font-weight: 500;
  text-transform: uppercase;
  text-transform: uppercase;

  color: color(neutral, 'light');
}
</style>
