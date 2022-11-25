<template>
  <main>
    <div class="content-container">
      <h1>Content goes here!</h1>
    </div>
    <div class="main-menu-container">
      <MainMenu />
    </div>
  </main>
</template>

<script>
import MainMenu from './MainMenu.vue';

export default {
  components: {
    MainMenu,
  },
  name: 'MainPage',
};
</script>

<style lang="scss" scoped>
.content-container {
  background-color: #1C1C1C;
  color: white;
  padding: 2rem 3rem;
}
.content-container h1 {
  max-width: 1200px;
  margin: 0 auto;
}
.main-menu-container {
  background-color: #0282F9;
}
</style>
