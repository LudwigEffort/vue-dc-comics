<template>
<ul>
  <li><img src="@/img/buy-comics-digital-comics.png" alt=""></li>
  <li><img src="@/img/buy-comics-merchandise.png" alt=""></li>
  <li><img src="@/img/buy-comics-subscriptions.png" alt=""></li>
  <li><img src="@/img/buy-comics-shop-locator.png" alt=""></li>
  <li><img class="test" src="@/img/buy-dc-power-visa.svg" alt=""></li>
</ul>
</template>

<script>
export default {
  name: 'MainMenu',
};
</script>

<style lang="scss" scoped>
ul {
  padding: 2rem 3rem;
  list-style: none;
  display: flex;
  gap: 1rem;
  max-width: 1200px;
  margin: 0 auto;
  justify-content: center;
}
.test {
  font-size: 12pt;
  color: white;
}
</style>
