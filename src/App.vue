<template>
  <div id="app">
    <div class="overlay"></div>
    <router-view/>
  </div>
</template>

<style scoped>
 #app {
  display: flex;
  align-items: center;
  justify-content: center;
  position: relative;
  width: 100vw;
  height: 100vh;
  overflow-y: auto;
 }

  .overlay {
    position: absolute;
    top: 0;
    bottom: 0;
    right: 0; 
    left: 0;
    background: url('./assets/background.png') no-repeat center center fixed; 
    -webkit-background-size: cover;
    -moz-background-size: cover;
    -o-background-size: cover;
    background-size: cover;
    opacity: 0.1;
  }
</style>
