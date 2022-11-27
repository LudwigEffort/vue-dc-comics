<template>
  <div>
    <img
      class="card"
      :src="imgUrl"
      alt=""
    >
    <h4>{{ series }}</h4>
  </div>
</template>

<script>
export default {
  name: 'CardPasta',
  props: {
    imgUrl: String,
    series: String,
  },
};
</script>

<style lang="scss" scoped>
  .card {
    cursor: pointer;
    text-align: center;
    img {
      max-width: 90%;
    }
    h4 {
      color: white;
    }
  }
</style>
