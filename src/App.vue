<template>
  <div id="app">
    <router-view/>
  </div>
</template>

<style>
@import url('./styles.css');

* {
  font-family: 'Roboto', sans-serif;
  padding: 0;
  margin: 0;
  box-sizing: border-box;
}

#app {
  min-height: 100vh;
  background-color: hsl(235, 18%, 26%);
}
</style>
