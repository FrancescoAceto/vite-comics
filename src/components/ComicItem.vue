<script>
export default {
  name: "ComicItem",
  data() {
    return {
    }
  },
  props: {
    thumb: String,
    title: String,
  }
}
</script>

<template>
  <div class="comic">
    <img class="comic-cover" :src="thumb" alt="comic cover">
    <div class="comic-title">{{ title }}</div>
  </div>
</template>

<style lang="scss" scoped>
  .comic {
    width: calc(100% / 6 - 10px / 6 * 5);
    color: white;
    padding: 50px;
    .comic-cover {
      width: 100%;
      aspect-ratio: 1/1;
      object-fit: cover;
      object-position: top;
      
    }
  }
</style>