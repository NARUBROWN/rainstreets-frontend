<script setup>
import { RouterLink, RouterView } from 'vue-router'
</script>

<template>
  <nav>
    <RouterLink to="/"><img class="logo" src="@/assets/logo.svg" alt="로고"></RouterLink>
    <RouterLink to="/"><img class="menu" src="@/assets/logo.svg" alt="로고"></RouterLink>
    <RouterLink to="/"><img class="menu" src="@/assets/logo.svg" alt="로고"></RouterLink>
  </nav>
  <div class="view">
    <RouterView/>
  </div>
  <footer>
    <table>
      <tr>
        <th>rainSTREET</th>
        <th>PRODUCT</th>
        <th>USEFUL LINKS</th>
        <th>CONTACT</th>
      </tr>
      <tr>
        <th>Lorem ipsum dolor sit amet</th>
        <th>Lorem ipsum</th>
        <th>Lorem</th>
        <th>Lorem ipsum dolor</th>
      </tr>
      <tr>
        <th>Lorem ipsum dolor sit amet</th>
        <th>Lorem ipsum</th>
        <th>Lorem</th>
        <th>Lorem ipsum dolor</th>
      </tr>
      <tr>
        <th>Lorem ipsum dolor sit amet</th>
        <th>Lorem ipsum</th>
        <th>Lorem</th>
        <th>Lorem ipsum dolor</th>
      </tr>
      <tr>
        <th>Lorem ipsum dolor sit amet</th>
        <th>Lorem ipsum</th>
        <th>Lorem</th>
        <th>Lorem ipsum dolor</th>
      </tr>
    </table>
    <h4>저작권 안내 멘트</h4>
  </footer>
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

.view {
  height: auto;
  min-height: 100vh;
  padding-bottom: 200px;
}

footer {
  height: 200px;
  padding-top: 15px;
  padding-bottom: 20px;
  background: #212121;
}

footer > table {
  margin: 0 auto;
  color: #fcfcfc;
}

tr > th{
  padding-top: 20px;
}

footer > h4 {
  margin-top: 20px;
  text-align: center;
  color: #fcfcfc;
}

</style>
