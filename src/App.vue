<template>
  <div class="wrapper">
    <router-view/>
  </div>
</template>

<style>
  @import url('https://fonts.googleapis.com/css2?family=Roboto+Condensed:wght@700&display=swap');

   html, body {
     padding: 0;
     margin: 0;

     font-family: 'Roboto Condensed', sans-serif;
   }

  h1, h2, h3, h4, h5, h6 {
    margin: 0;
  }

  .wrapper {
    width: 100vw;
    height: 100vh;

    background: url('./assets/background-image.svg');
  }

</style>
