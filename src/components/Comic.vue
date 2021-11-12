<template>
  <div class="preview">
    <img :src="thumb" />
    <h2>{{ series }}</h2>
  </div>
</template>

<script>
export default {
  props: {
    thumb: String,
    series: String,
  },
};
</script>

<style lang="scss">
.preview {
  margin-top: 50px;
  padding: 0 4px;
  img {
    object-fit: none;
    object-position: 50% 0px;
    height: 200px;
    width: 200px;
  }
  h2 {
    font-size: 1rem;
    max-width: 192px;
  }
}
</style>
