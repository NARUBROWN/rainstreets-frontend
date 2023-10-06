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
  display: flex;
  width: 100%;
  height: 100%;
  min-height: 100vh;
  background: #005db4;
  flex-direction: column;
  justify-content: center;
  align-items: center;
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
  text-align: center;
  border: 1px solid var(--blue-card-text);
  padding-top: 10px;
  padding-bottom: 10px;
}

#button:hover {
  background: var(--blue-card-text);
}

#button:hover a {
  color: black;
}

#button > a {
  color: var(--blue-card-text);
  text-decoration-line: none;
  font-size: 15pt;
  font-weight: lighter;
}

#productName {
  color: var(--blue-card-text);
  font-weight: bold;
  font-size: 15pt;
  text-align: center;
}


@media all and (min-width:1025px) {
  #message {
    font-size: 45pt;
  }

  #productName {
    font-size: 20pt;
  }
}

</style>