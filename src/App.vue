<script setup>
import { RouterLink, RouterView } from 'vue-router'
</script>

<template>
  <nav>
    <div id="left">
      <RouterLink to="/">
        <img class="logo" src="@/assets/logo.svg" alt="로고">
      </RouterLink>
      <RouterLink to="/">
        <h1 id="logoText">rainStreet</h1>
      </RouterLink>
    </div>
    <ul>
      <RouterLink to="">메뉴1</RouterLink>
      <RouterLink to="">메뉴2</RouterLink>
      <RouterLink to="">메뉴3</RouterLink>
    </ul>
    <div id="right">
      <RouterLink to="/"><img class="menu" src="@/assets/logo.svg" alt="로고"></RouterLink>
    </div>
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
  height: 6vh;
  background-color: var(--card);
  display: grid;
  grid-template-columns: minmax(30px, 1fr) 2fr 1fr;
  position: relative;
}

#left {
  padding-top: 10px;
  padding-left: 10px;
  display: flex;
}

#right {
  padding-top: 10px;
  padding-right: 10px;
}

img {
  width: 40px;
}

.menu {
  width: 40px;
  float: right;
}

ul {
  margin-block-start: 1.2em;
  margin-block-end: 1.2em;
  text-align: center;
}

ul > a {
  font-size: 13pt;
  margin-left: 5%;
  margin-right: 5%;
  color: var(--text-color);
  text-decoration-line: none;
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

tr > th {
  padding-top: 20px;
}

footer > h4 {
  margin-top: 20px;
  text-align: center;
  color: #fcfcfc;
}

#logoText {
  margin-top: 7px;
  margin-left: 10px;
  color: var(--text-color);
  font-weight: bolder;
  font-size: 16pt;
}

a {
  text-decoration-line: none;
}

@media all and (min-width:1025px) {
  #left {
    padding-left: 60%;
  }

  #right {
    padding-right: 60%;
  }
}
</style>
