<script setup>
</script>

<template>
<div id="fullPage">
  <div id="productName">
    <h1>PRODUCT NAME</h1>
  </div>
  <div id="message">
    <h1>세상에서 가장 뛰어난<br>궁극의 창작도구</h1>
  </div>
  <div id="button">
    <router-link to="">확인하기</router-link>
  </div>
</div>
</template>

<style scoped>
#fullPage {
  min-height: 100vh;
  background: #005db4;
}

#message {
  margin-top: 15px;
  text-align: center;
  color: var(--blue-card-text);
  font-size: 35pt;
  line-height: 1.3em;
  font-weight: bold;
  margin-bottom: 20px;
}

#button {
  width: 100px;
  margin: 0 auto;
  text-align: center;
  border: 1px solid var(--blue-card-text);
  padding-top: 10px;
  padding-bottom: 10px;
}

#button > a {
  text-decoration-line: none;
  color: var(--blue-card-text);
  font-size: 15pt;
  font-weight: lighter;
}

#productName {
  color: var(--blue-card-text);
  font-weight: bold;
  font-size: 15pt;
  text-align: center;
}
</style>