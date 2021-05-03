<template>
  <div class="main-container">
    <div class="todo-list"></div>
    <div class="short-term"></div>
    <div class="mid-term"></div>
    <div class="long-term"></div>
  </div>
</template>

<style scoped>
.main-container {
  width: auto;
  height: 1200px;
  background-color: rgb(114, 158, 235);
  display: flex;
  padding-top: 20px;
}

.main-container div {
  width: 80px;
  height: 160px;
  background-color: rgb(211, 235, 114);
  border: 2px solid black;
  /* margin-left: 10px; */
}
</style>
