<script setup>
import { RouterLink, RouterView } from 'vue-router'
</script>

<template>
  <nav>
    <RouterLink to="/"><img class="logo" src="@/assets/logo.svg" alt="로고"></RouterLink>
    <RouterLink to="/"><img class="menu" src="@/assets/logo.svg" alt="로고"></RouterLink>
    <RouterLink to="/"><img class="menu" src="@/assets/logo.svg" alt="로고"></RouterLink>
  </nav>
  <RouterView />
</template>
<style scoped>
nav {
  width: 100%;
  height: 20%;
  background-color: var(--card);
}

nav > a > img {
  margin: 10px 0 10px 10px;
  width: 50px;
}

.menu {
  float: right;
  margin: 10px 10px 10px 10px;
  width: 50px;
}

</style>
