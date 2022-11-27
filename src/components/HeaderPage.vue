<template>
  <header>
    <img
      src="@/img/dc-logo.png"
      alt=""
    >
    <ul>
      <li>Characters</li>
      <li>Comics</li>
      <li>Movies</li>
      <li>TV</li>
      <li>Games</li>
      <li>Collectibles</li>
      <li>Videos</li>
      <li>Fans</li>
      <li>News</li>
      <li>Shop</li>
    </ul>
  </header>
</template>

<script>
export default {
  name: 'HeaderPage',
};
</script>

<style lang="scss" scoped>
header {
  max-width: 1200px;
  margin: 0 auto;
  padding: 1rem;
  display: flex;
  flex-direction: row;
  justify-content: space-between;
  align-items: center;
}
header ul {
  font-size: 1.3rem;
  list-style: none;
  display: flex;
  gap: 1rem;
}
header li:hover {
  cursor: pointer;
  color: blue;
  border-bottom: 2px solid blue;
}
</style>
