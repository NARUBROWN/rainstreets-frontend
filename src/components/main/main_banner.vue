<script setup>
</script>

<template>
  <div class="card">
    <h1>제목</h1>
    <div class="imageBox"></div>
  </div>
</template>

<style scoped>
.card {
  z-index: -1;
  margin: 10px auto;
  border-radius: 10px;
  width: 95.56%;
  padding: 10px 0 10px 0;
  background-color: var(--card);
  color: var(--text-color);
}

.card > h1 {
  margin: 8px 0 10px 0;
  padding: 0 0 0 25px;
  font-size: 9pt;
  font-weight: bold;
}

.imageBox {
  margin: 0 auto;
  width: 95.56%;
  height: 300px;
  border-radius: 10px;
  background: var(--page-color);
}
</style>