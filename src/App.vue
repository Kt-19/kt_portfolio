<script setup>
import Left from './components/Left.vue';
import Right from './components/Right.vue';
</script>

<template>
  <header>
    <img alt="Vue logo" class="logo" src="./assets/minion.png" width="240" height="265">
    <Left msg="Leong Kean Toh - 梁健涛" />
  </header>

  <main>
    <Right />
  </main>
</template>

<style scoped>
header {
  line-height: 1.5;
}

.logo {
  display: block;
  margin: 0 auto 0.5rem;
}

@media (min-width: 1024px) {
  header {
    display: flex;
    flex-direction: column;
    justify-content: center;
    align-items: center;
  }
}
</style>
