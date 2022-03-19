<template>
  <div class="subtitles">
    <p class="subtitle">
      marca: <b>{{ brand }}</b>
    </p>
    <p class="subtitle">
      modelo: <b>{{ model }}</b>
    </p>
    <p class="subtitle">
      ano: <b>{{ year }}</b>
    </p>
  </div>
</template>

<script lang="ts">
import vue from 'vue'

export default vue.extend({
  props: {
    brand: {
      type: String,
      required: true,
    },
    model: {
      type: String,
      required: true,
    },
    year: {
      type: String,
      required: true,
    },
  },
})
</script>

<style lang="scss" scoped>
.subtitles {
  display: flex;
  flex-direction: row;
  align-items: flex-start;
  gap: 8px;

  .subtitle {
    font-family: Inter;
    font-size: 10pt;
    font-weight: 200;
    color: color(neutral, 'light');
  }
}
</style>
