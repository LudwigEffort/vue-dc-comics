<template>
  <ul>
    <li>
      <img
        src="@/img/buy-comics-digital-comics.png"
        alt="1"
      >
      <h4>Digital Comics</h4>
    </li>
    <li>
      <img
        src="@/img/buy-comics-merchandise.png"
        alt="1"
      >
      <h4>Digital Comics</h4>
    </li>
    <li>
      <img
        src="@/img/buy-comics-subscriptions.png"
        alt="1"
      >
      <h4>Digital Comics</h4>
    </li>
    <li>
      <img
        src="@/img/buy-comics-shop-locator.png"
        alt="1"
      >
      <h4>Digital Comics</h4>
    </li>
    <li>
      <img
        src="@/img/buy-dc-power-visa.svg"
        alt="1"
        class="test"
      >
      <h4>Digital Comics</h4>
    </li>
  </ul>
</template>

<script>
export default {
  name: 'MainMenu',
};
</script>

<style lang="scss" scoped>
img {
  max-width: 50px;
  max-height: 50px;
  margin-right: 0.5rem;
}
ul {
  cursor: pointer;
  padding: 2rem 3rem;
  list-style: none;
  display: flex;
  flex-wrap: wrap;
  gap: 1rem;
  max-width: 1200px;
  margin: 0 auto;
  justify-content: center;
}
li {
  flex: 0 0 calc((100% - 4rem) / 5);
  display: flex;
  align-items: center;
  h4 {
    color: white;
  }
}
</style>
